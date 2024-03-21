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
        stage('copy build') { 
            steps {
                // Copy the 'dist' folder to the desired location
                bat 'xcopy "D:/react-jenkins/dist" "C:\Users\user\Desktop" /s /e'
                // You can replace "%USERPROFILE%/Desktop" with any desired folder path
            }
        }
    }
}