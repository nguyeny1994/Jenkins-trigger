pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...${BUILD_NUMBER}'
                scripts{
                    sh"echo ${BUILD_NUMBER}"
                }
            }
        }
    }
}
