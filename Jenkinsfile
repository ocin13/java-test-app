pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                 script {
                    echo 'Testing..'
                    cd src/main/java/
                    javac JavaApplication.java
                    java JavaApplication
                }
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
