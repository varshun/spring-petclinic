pipeline {
  agent any
  
  tools {
            jdk "JAVA_HOME"
        }
  
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
  
