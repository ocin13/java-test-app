pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat "cd src"
                bat "cd main"
                bat "cd java
                bat "javac JavaApplication.java"
                bat "java JavaApplication"
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
