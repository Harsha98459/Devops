pipeline {
    agent any // Tells Jenkins to run this pipeline on any available executor

    stages {
        stage('Checkout') {
            steps {
                echo 'Checking out source code...'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the application...'
            }
        }
        stage('Test') {
            steps {
                echo 'Running unit tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application to production...'
            }
        }
    }
}
