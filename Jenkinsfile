pipeline {
    
    agent any
    
    tools {
        jdk 'jdk17'
        maven 'maven3'
    }


    stages {
        
        stage('COMPILE') {
            steps {
                sh 'mvn compile'
            }
        }
        stage('TEST') {
            steps {
                sh 'mvn test'
            }
        }
        stage('PACKAGE') {
            steps {
                sh 'mvn package'
            }
        }
    }
}
