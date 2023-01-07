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
                sh 'echo "I added this only in the main branch!"'
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo "Deploying..."' 
            }
        }
    }
}
