pipeline {
    agent any
	
    stages {
        stage('Clean') {
            steps {
               bat "mvn clean"
            }
        }
        stage('Build') {
            steps {
                bat "mvn build"
            }
        }
        stage('Test') {
            steps {
                bat 'mvn test'
            }
        }
    }
}