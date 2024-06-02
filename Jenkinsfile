pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                build 'simple-java-maven-app'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
