pipeline {
    agent any
    stages {
        stage('cloneproject') {
            steps {
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
