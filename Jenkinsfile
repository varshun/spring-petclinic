pipeline {
  agent any
  
  stages{
    stage('Clean'){
        steps
      {
        withMaven(maven : 'apache-maven-3.6.3') {
            bat 'mvn clean' 
        }
      }  
    }
  }
}
  
