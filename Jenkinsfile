pipeline {
  agent any
  
  stages {
        
    stage('Git') {
      steps {
        git 'https://github.com/Snavales11/node-hello.git'
      }
    }
     
    stage('Build') {
      steps {
        sh 'npm install'
        sh 'npm start'
      }
    }  
  }
} 
