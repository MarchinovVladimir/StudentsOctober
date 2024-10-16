pipeline {
    agent any
    stages {
        stage('NPM Install') {
            steps {
                bat 'npm install'
            }
        } 
        stage('Execute tests') {
            steps {
                bat 'npm run test'
            }
        } 
        stage('Deploy to Staging') {
            steps {
                echo 'Deploy to Staging'
            }
        } 
        stage('Deploy to Production') {
            steps {
                echo 'Deploy to Production'
            }
        }       
    }
}
