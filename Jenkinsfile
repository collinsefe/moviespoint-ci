pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Service password is SERVICE_CREDS_PSW"'
            }
        }
        stage('Test') {
            steps {
                sh 'make check || true' 
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "SSH private key is located at SSH_CREDS"'
            }
        }
    }
}


