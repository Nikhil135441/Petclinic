pipeline {
    agent any   
    stages{
        stage("Compile"){
            steps{
                sh "mvn clean compile"
            }
        }
        
         stage("Test Cases"){
            steps{
                sh "mvn test"
            }
        }
        
         stage("Build"){
            steps{
                sh " mvn clean install"
            }
        }
    }   
}        
