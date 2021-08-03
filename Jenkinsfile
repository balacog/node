pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying'
            }
        }
    }
}