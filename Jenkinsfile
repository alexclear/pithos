pipeline {
    agent any
    stages {
        stage('Build an uberjar') {
            steps {
                sh "lein uberjar"
            }
        }
    }
}
