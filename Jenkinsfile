pipeline {
    agent any
    stages {
        stage('Installing dependencies') {
            steps {
                bat 'npm install'
            }
        }
        stage('Running tests') {
            steps {
                bat 'npm run test'
            }
        }
    }
}
