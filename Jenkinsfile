pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/2100032578cse/cdexam.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                // Add deployment steps here
            }
        }
    }
}
