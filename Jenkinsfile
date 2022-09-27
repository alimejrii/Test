pipeline {
    agent any

    stages {
        stage('SCM Checkout') {
            steps {
                echo 'Checkout Completed..'
            }
        }
        stage('Build') {
            steps {
                echo 'Test Completed..'
            }
        }
        stage('Test') {
            steps {
                echo 'Test Completed..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy Completed..'
                sh 'date'
            }
        }     
    }
}
