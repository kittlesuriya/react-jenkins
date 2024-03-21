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
        stage('Run Dev') { 
            steps {
                dir("D:/react-jenkins"){
                    bat 'npm run dev' 
                }
            }
        }
    }
}