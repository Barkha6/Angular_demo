pipeline{
  agent any
  
  stages{
    stage('Install'){
      steps{
        sh "ng install"
      }
    }
    stage('Build'){
      steps{
        sh "ng build"
      }
    }
  }
}
