pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/syedrizwanabbas/pipeline.git'
            }
        }
        stage('Build') {
            steps {
                // Example for compiling code, adjust accordingly
                sh 'echo "Building Project"'
            }
        }
        stage('Test') {
            steps {
                // Example for running tests
                sh 'echo "Running Tests"'
            }
        }
        stage('Deploy') {
            steps {
                // Example for deployment step
                sh 'echo "Deploying"'
            }
        }
    }
}
