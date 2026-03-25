pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Jenkins automatically pulls from GitHub (SCM)
                echo "Code fetched from GitHub"
            }
        }

        stage('Build') {
            steps {
                echo "Build started"
            }
        }

        stage('Test') {
            steps {
                echo "Running tests"
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application"
            }
        }
    }
}
