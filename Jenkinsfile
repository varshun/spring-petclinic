pipeline {
    agent any
    stages{
        stage('Clean'){
            steps{
                bat 'mvn --version'
                bat 'mvn clean'
            }
        }
    }
}
