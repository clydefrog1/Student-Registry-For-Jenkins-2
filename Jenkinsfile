pipeline {
    agent any
    stages {
        stage('Installing dependencies') {
            steps {
                bat 'npm install'
            }
        }
        stage('Starting the application') {
            steps {
                bat 'npm run start'
            }
        }
        stage('Running tests') {
            steps {
                bat 'npm run test'
            }
        }
    }
}
