pipeline {
    
    agent any
    
    options {
        buildDiscarder(logRotator(numToKeepStr: '5', artifactNumToKeepStr: '5'))
    }
    
    stages{
        stage("Code Checkut"){
            steps{
                git branch: 'main', url: 'https://github.com/Jayesh321/dev.git'
            }
        }
    }
}