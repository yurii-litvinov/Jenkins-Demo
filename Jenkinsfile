pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('build') {
            steps {
                cmd /C "mvn --version"
            }
        }
    }
}