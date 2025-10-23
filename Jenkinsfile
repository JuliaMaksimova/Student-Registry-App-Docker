pipeline {
    agent any
    stages {
        stage('Install Dependancies') {
            steps {
                bat 'npm install'
            }
        }
        stage('Test') { 
            steps {
                bat 'npm run test' 
            }
        }
    }
}