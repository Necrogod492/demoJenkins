pipeline {
  agent any
  tools {
    nodejs 'nodejs'
  }

  stages {
    stage('Build'){
      steps{
        echo 'Building...'
        sh 'npm install'
      }
    }
    stage('Test'){
      steps{
        sh 'npm test'
        echo 'Testing'
      }
    }
    stage('Deploy / Deliver'){
      steps{
        echo 'Deploying...'
      }
    }
  }
}