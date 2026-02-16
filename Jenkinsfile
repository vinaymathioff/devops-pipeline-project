pipeline {
    agent any

    stages {

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t ivinaym/devops-app .'
            }
        }

        stage('Push to DockerHub') {
            steps {
                sh 'docker push ivinaym/devops-app'
            }
        }
    }
}
