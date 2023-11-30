pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh './script.sh'
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
