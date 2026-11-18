
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo "Checking branch: ${env.BRANCH_NAME}"
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building UIRI Manufacturing Resource Management System'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing application'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage completed'
            }
        }
    }
}
