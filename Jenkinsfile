pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            steps {
            sh 'docker images'
        }
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
