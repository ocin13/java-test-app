pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                dir('src'){
                    sh 'pwd'
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
