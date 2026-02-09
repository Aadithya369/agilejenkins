pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo "Build stage - Updated version"
            }
        }

        stage('Test') {
            steps {
                echo "Executing test cases"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application to production"
            }
        }

        stage('Post-Deployment') {
            steps {
                echo "Post deployment verification completed"
            }
        }
    }
}

