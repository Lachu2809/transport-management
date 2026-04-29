pipeline {
    agent any

    tools {
        maven 'Maven'
    }

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/YOUR_USERNAME/transport-management.git'
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean package'
            }
        }

        stage('Test') {
            steps {
                echo 'No backend tests for frontend project'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deployment stage will be added later'
            }
        }
    }
}