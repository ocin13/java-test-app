pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'cd C:\Users\15512\.jenkins\workspace\test-pipeline'
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
