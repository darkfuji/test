pipeline {
    agent { docker { image 'node:13.7-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
