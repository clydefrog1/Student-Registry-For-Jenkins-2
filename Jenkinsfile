pipeline {
    agent any

    stages {
		stage('Installing dependencies') {
            steps {
                echo 'Installing dependencies..'
				bat 'npm install'
            }
        }
		stage('Starting the application') {
            steps {
                echo 'Starting the application..'
				bat 'npm run start'
            }
        }
		stage('Running tests') {
            steps {
                echo 'Running tests..'
				bat 'npm run test'
            }
        }
    }
}