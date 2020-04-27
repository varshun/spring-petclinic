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
        tools {
                   jdk "JAVA_HOME"
                }
        withMaven(maven : 'MAVEN_HOME') {
            bat 'mvn test' 
        }
      }  
    }
  }
}
  
