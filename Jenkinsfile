pipeline {
    agent {
        docker { image 'python:latest' }
    }
    stages {
        stage('build') {
            steps {
                bat 'python --version'
            }
        }
    }
}
