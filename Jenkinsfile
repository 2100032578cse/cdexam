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
                sh 'buildingl'
            }
        }
        stage('Test') {
            steps {
                sh 'test'
            }
        }
        stage('Deploy') {
            steps {
               sh"deploying"
            }
        }
    }
}
