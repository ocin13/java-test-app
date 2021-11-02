pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'java -version'
                sh 'git -version'
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
