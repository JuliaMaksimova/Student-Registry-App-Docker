pipeline {
    agent any
    stages {
        stage('Install Dependancies') {
            steps {
                bat 'npm install'
            }
        }
        stage('Run Security Tests') { 
            steps {
                bat 'npm audit' 
            }    
        }
        stage('Run integration test') { 
            steps {
                bat 'npm run test' 
            }
        }
    }
}