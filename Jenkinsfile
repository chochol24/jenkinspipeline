pipeline {
    agent any
    tools {
        maven "M3"
    }
    stages {
        stage('Build') {
            steps {
                sh "mvn clean compile -X"
            }
        }
        stage('Test') {
             steps {
                 sh "mvn test -X"
             }
        }
    }
}