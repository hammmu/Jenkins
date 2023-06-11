pipeline {
    environment {
        PATH = "C:\\WINDOWS\\SYSTEM32;C:\\Program Files\\Docker\\Docker\\resources\\bin"
    }
    agent any
    stages {
        stage('Build Docker Image') {
            steps {
                bat 'docker build -t my-flask-app .'
            }
        }
    }
}
