#!groovy​

pipeline {
    agent { docker 'python:3.6.1' }
    stages {
        stage('build') {
            steps {
                bat 'python --version'
            }
        }
    }
}