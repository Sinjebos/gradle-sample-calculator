pipeline {
    agent any
    stages {
    stage('Build'){
        steps{
            sh './gradlew classes'
            }
        }
    stage('Test'){
        steps {
            sh './gradlew test'
            }
        }
    stage('Deploy'){
        steps{
            sh './gradlew jar'
        }
    }
    }
}
