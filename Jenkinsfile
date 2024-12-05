pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'Build-testing'
            }
        }
        stage('Test') {
            steps {
                sh 'uint-Test-testing'
            }
        }
        stage('Deploy') {
            steps {
                sh 'Deploy-testing'
            }
        }
    }
}