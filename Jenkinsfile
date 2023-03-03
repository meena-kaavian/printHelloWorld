pipeline{
    agent any
    
    tools{nodejs "node"}
    
    stages{
        stage('Build'){
            steps{
                git credentialsId: 'Meenakshi', url: 'https://github.com/meena-kaavian/printHelloWorld.git'
                bat 'npm install'
            }
        }
    }
}