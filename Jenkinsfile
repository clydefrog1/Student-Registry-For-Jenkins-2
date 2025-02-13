pipeline {
    agent any
    stages {
        stage('Installing dependencies') {
            steps {
				'npm install'
            }
        }
        stage('Starting the application') {
            steps {
				'npm run start'
            }
        }
		stage('Running tests') {
            steps {
				'npm run test'
            }
        }
    }
}