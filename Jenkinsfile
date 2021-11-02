pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat "cd src/main/java  javac JavaApplication.java java JavaApplication"
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
