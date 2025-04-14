pipeline {
    stages {
        stage('clone code') {
            steps {
                checkout scm
            }
        }

        stage('installing required dependencies') {
            steps {
                sh "npm install"
            }
        }
    }
}
