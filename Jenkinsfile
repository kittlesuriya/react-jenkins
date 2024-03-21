pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
        stage('Run Dev') { 
            steps {
                sh 'npm run dev' 
            }
        }
    }
}