pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'cd src/main/java'
                bat 'javac JavaApplication.java'
                bat 'java JavaApplication'
            }
        }
        stage('Test') {
            steps {
                echo 'hello'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
