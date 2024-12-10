pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git credentialsId: 'integration', url: 'https://github.com/sangeeth033/jenkins-integration.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Building the project..."'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Running tests..."'
            }
        }
    }
}
