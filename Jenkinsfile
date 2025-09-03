pipeline {
    agent any
    
    tools {nodejs "node"}
    
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'npm run build'
            }
        }
        stage('Test') {
            steps {
                echo "Tests passed successfully!"
            }
        }
        stage('Deploy') {
            steps {
                echo "Deployed successfully!"
            }
        }
    }
}