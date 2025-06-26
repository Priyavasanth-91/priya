pipeline {
    agent any
    stages {
        stage('cloneproject') {
            steps {
                git credentialsId: 'Priyavasanth-91', branch: 'branch1', url: 'https://github.com/Priyavasanth-91/priya/new/branch1'
            }
        }
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
