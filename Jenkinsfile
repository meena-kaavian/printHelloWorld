pipeline{
    agent any
    
    tools{nodejs "node"}
    
    stages{
        stage('Build'){
            steps{
                git 'https://github.com/Kaavian-Systems-Pvt-Ltd/employee-checkin-system.git'
                bat 'npm install'
            }
        }
    }
}