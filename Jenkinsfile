pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
               sh 'java JavaApplication'  
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
