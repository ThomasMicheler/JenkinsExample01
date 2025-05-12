pipeline {
    agent { docker { image 'python:3.13.3-alpine3.21' } }
    stages {
        stage('build') {
            steps {
                echo 'Pipeline started.'
                sh 'python3 --version'
            }
        }
    }
}
