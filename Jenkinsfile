// pipeline {
//     agent { docker { image 'node:19-alpine' } }
//     stages {
//         stage('build') {
//             steps {
//                 sh 'node --version'
//             }
//         }
//     }

pipeline {
    agent any
    stages {
        stage('Build') {
            agent {
                docker {
                    image 'node:19-alpine'
                    reuseNode true
                }
            }
            steps {
                sh 'node --version'
            }
        }
    }
}