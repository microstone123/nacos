pipeline {
    agent { docker 'maven:3.8.6' }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
