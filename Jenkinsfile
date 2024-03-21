pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                dir("D:/react-jenkins"){
                    sh 'npm install' 
                }
            }
        }
        stage('Run Dev') { 
            steps {
                dir("D:/react-jenkins"){
                    sh 'npm run dev' 
                }
            }
        }
    }
}