// Jenkins pipeline
pipeline {
    agent any

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

        stage('Running app locally') {
            steps {
                sh "node app.js"
            }
        }
    }
}
