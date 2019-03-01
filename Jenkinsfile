pipeline {
    agent {
        docker { image 'python' }
    }
    stages {
        stage('build') {
            steps {
                bat 'python --version'
            }
        }
    }
}
