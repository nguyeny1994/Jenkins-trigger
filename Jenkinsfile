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
                echo 'Deploying......test....${BUILD_NUMBER}'
                script{
                    sh"echo ${BUILD_NUMBER}"
                }
            }
        }
    }
}
