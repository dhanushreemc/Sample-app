pipeline {
    agent { label "build" }
    stages {
        stage('checkout') {
            steps {
                checkout scm
            }
        }
        stage('Build') {
            steps {
                sh "this is for test demo"
            }
        }
    }
}
