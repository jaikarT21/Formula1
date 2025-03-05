pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/jaikarT21/Formula1.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building project..."'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying project..."'
            }
        }
    }
}