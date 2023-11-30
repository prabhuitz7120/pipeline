pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                docker compose -f docker-compose-quickstart.yml up -d
            }
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
