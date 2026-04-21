pipeline {
    agent any

    stages {
        stage('Build Docker Image') {
            steps {
                bat 'docker build -t ayushrwt15/lab11-devops .'
            }
        }

        stage('Push to Docker Hub') {
            steps {
                bat 'docker push ayushrwt15/lab11-devops'
            }
        }
    }
}