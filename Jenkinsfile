pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Etapa sin implementacion'
            }
        }
        stage('Test') {
            steps {
                echo 'Etapa sin implementacion'
            }
        }
        stage('Deploy') {
            steps {
                sh 'docker-compose down -v --rmi all'
                sh 'docker network prune --force'
                sh 'docker-compose up -d --build'
            }
        }
    }
}