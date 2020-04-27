pipeline {
  agent any
  
  stages{
    stage('Clean'){
        steps
      {
        withMaven(maven : 'MAVEN_HOME') {
            bat 'mvn clean' 
        }
      }  
    }
     stage('Test'){
        steps
      {
        withMaven(maven : 'MAVEN_HOME') {
            bat 'mvn test' 
        }
      }  
    }
  }
}
  
