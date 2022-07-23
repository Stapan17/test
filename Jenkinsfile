#!groovy
pipeline {
    agent none
   stages {     
    stage('Maven Install') {
      agent {         
       docker {          
         image 'python:3.8'         
     }       
  }       
  steps {
       sh 'python --version'
       }
     }
   }
 }
