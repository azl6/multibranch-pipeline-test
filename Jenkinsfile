pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                sh 'echo "Building..."' 
            }
        }
        stage('Test') { 
            steps {
                sh 'echo "I wrote this only in DEV!"'
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo "Deploying..."' 
            }
        }
    }
}
