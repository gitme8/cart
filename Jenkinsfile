pipeline {
    agent {
        label 'workstation'
    }

    triggers {
        pollSCM('*/2 * * * *')
    }

    stages {
        stage('compile the code') {
            steps {
                sh 'compiling code'
            }
        }
    }

        stage('check the Code Quality') {
            steps {
                sh 'Checking Code Quality'
            }
        }

        stage('Test Cases')
            steps {
                sh 'Test Cases'
            }
        }
    }
}
