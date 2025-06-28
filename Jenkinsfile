pipeline {
    agent any
    stages {
        stage('mvn version') {
            steps {
                    sh 'mvn --version'
            }
        }
        stage('git version') {
            steps {
                    sh 'git --version'
            }
        }
    }
}
   