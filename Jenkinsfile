pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            steps {
            sh """#!/bin/bash
            ls -l
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
