pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh './docker-compose-quickstart.yml'

        }
        stage('Test') {
            steps {
                echo 'Testing..'
                docker images
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
