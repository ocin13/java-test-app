pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                script{
                    cd src/main/java/
                }
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
