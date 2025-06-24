pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Date') {
            steps {
                sh 'date'
            }
        }
        stage('maven version') {
            steps {
                sh 'mvn --version'
            }
        }
       stage('java') {
            steps {
                sh 'java --version'
            }  
        
       }
    }
}
