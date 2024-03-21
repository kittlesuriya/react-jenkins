pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                dir("D:/react-jenkins"){
                    bat 'npm install' 
                }
            }
        }
        stage('Run build') { 
            steps {
                dir("D:/react-jenkins"){
                    bat 'npm run build' 
                }
            }
        }
    }
}