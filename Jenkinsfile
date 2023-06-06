pipeline {
    agent any
    //tools {        
        //nodejs "NodeJS 12.3.1"
    //}
    stages { 
        stage('Checkout') {
            steps {
                git 'https://github.com/Barkha6/Angular_demo.git'
            }
        }
        stage('Build') {
            steps {
                sh'''
                npm install && ng build --prod
                '''
            }
        }
    }
}
