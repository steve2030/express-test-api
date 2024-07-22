pipeline {
    agent any

    stages {
        stage('Stage 1') {
            steps {
                echo 'Hello from Stage 1'
            }
        }
        stage('Checkout') {
            steps {
                checkout scm
                echo 'Checked out code from Git'
            }
        }
        stage('Stage 3') {
            steps {
                echo 'Hello from Stage 3'
            }
        }
        stage('Stage 4') {
            steps {
                echo 'Hello from Stage 4'
            }
        }
        stage('Stage 5') {
            steps {
                echo 'Hello from Stage 5'
            }
        }
    }

    post {
        always {
            echo 'Pipeline execution completed.'
        }
    }
}
