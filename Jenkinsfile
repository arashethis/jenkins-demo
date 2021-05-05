pipeline {
    agent { docker { image 'hub.c.163.com/library/node:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}