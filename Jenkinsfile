pipeline {
    environment {
        PATH = "C:\\WINDOWS\\SYSTEM32;C:\\Users\\Hammas Ahmed\\AppData\\Local\\Programs\\Python\\Python310\\"
    }
    agent any
    stages {
        stage('Build Docker Image') {
            steps {
                bat 'python main.py'
            }
        }
    }
}
