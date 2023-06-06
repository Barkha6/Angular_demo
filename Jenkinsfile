pipeline {
    agent any
    tools {        
        nodejs "NodeJS 12.3.1"
    }
    stages { 
        stage('Checkout') {
            steps {
                git 'https://github.com/arperrin/sample-angular.git'
            }
        }
        stage('Build') {
            steps {
                sh'''
                npm install && ng build --prod
                '''
            }
        }
