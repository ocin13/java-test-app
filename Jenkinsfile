pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'cd src'
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
