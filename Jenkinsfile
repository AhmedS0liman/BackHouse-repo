pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                sh 'docker login -u ahmeds0liman -p 241998Ahmed'
                sh 'docker build -t back_house/web-image:latest . '
                sh 'docker push back_house/web-image:latest'
            }
        }
    }
} 
