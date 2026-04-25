pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/Ayushhh-15/lab11-devops.git'
            }
        }

        stage('Build Docker Image') {
            steps {
                bat 'docker build -t ayushrwt15/lab11-devops .'
            }
        }

        stage('Push Docker Image') {
            steps {
                bat 'docker push ayushrwt15/lab11-devops'
            }
        }
    }
}
