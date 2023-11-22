pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                sh 'sudo docker login -u ahmed.soliman241998@gmail.com -p 241998Ahmed'
                sh 'sudo docker build -t back_house/web-image:latest . '
                sh 'sudo docker push back_house/web-image:latest'
            }
        }
    }
} 
