pipeline {
    agent any
    tools {
        maven 'Maven'  // Use the exact name you set in Global Tool Configuration
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }
        stage('Test') {
            steps {
                bat 'mvn test'
            }
        }
    }
}
