
pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Source code checkout completed'
            }
        }

        stage('Build') {
            steps {
                echo 'Building application'
                sh 'whoami'
                sh 'java -version'
            }
        }

        stage('Test') {
            steps {
                echo 'Application testing started'
                sh 'echo Testing successful'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage completed'
            }
        }
    }
}
