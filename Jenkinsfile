pipeline {
    agent any
    tools{
        maven 'maven'
        jdk 'java'
    }

    stages {
        stage('Build') {
            steps {
                    bat 'mvn clean'
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
