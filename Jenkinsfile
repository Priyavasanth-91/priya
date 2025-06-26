pipeline {
    agent any
    stages {
        stage('Clean') {
            steps {
                    sh 'mvn clean'
            }
        }

        stage('Compile') {
            steps {
                    sh 'mvn compile'
            }
        }

        stage('Build') {
            steps {
                    sh 'mvn package'
            }
        }
    }
}
