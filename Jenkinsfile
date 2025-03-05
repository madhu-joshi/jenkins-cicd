pipeline {
    agent { docker { image 'node:19-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'node --version'
            }
        }
    }
}