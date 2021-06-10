pipeline {
    agent {
        docker {image 'node:14-alpine'}
    }
    stages {
        stage('docker node version') {
            steps {
                sh 'node --version'
            }
        }
    }
}
