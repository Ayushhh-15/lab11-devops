pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/Ayushhh-15/lab11-devops.git'
            }
        }

        stage('Build Docker Image') {
            steps {
                bat 'docker build -t ayushhh-15/lab11-devops .'
            }
        }
    }
}
