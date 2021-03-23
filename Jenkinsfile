pipeline {
    agent { docker { image 'node:13.7.0' } }
    stages {
        stage('build') {
            steps {
                sh 'npm --version'
            }
        }
    }
}
