/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'python:3.10.7-alpine', image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
