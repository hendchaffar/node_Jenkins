pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                echo "hello world"
            }
            }
         stage('Build Docker Image') {
            steps {
        // Build Docker image
                sh 'docker build -t node-app .'
            }
            }
    }
}    
