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
                   jdk "jdk-1.8.251"
                }
        withMaven(maven : 'MAVEN_HOME') {
            bat 'mvn test' 
        }
      }  
    }
  }
}
  
