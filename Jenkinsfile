pipeline {
    agent { docker { image 'node:18.17.1-alpine3.18' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}
