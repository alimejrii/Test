pipeline {
    agent any

    stages {
        stage('SCM Checkout') {
            steps {
                echo 'Checkout Completed..'
            }
        }
    stages {
        stage('Build') {
            steps {
                echo 'Test Completed..'
            }
        }
    stages {
        stage('Test') {
            steps {
                echo 'Test Completed..'
            }
        }
    stages {
        stage('Deploy') {
            steps {
                echo 'Deploy Completed..'
                sh 'date'
            }
        }     
    }
}
