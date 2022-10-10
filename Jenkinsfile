pipeline {
    agent any 
    stages {
        stage('checkout') { 
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[credentialsId: '0584edd4-6d77-4b79-b877-f016c35c5ec8', url: 'https://github.com/SaravanaVedha/Calendar-war.git']]])
            }
        }
        stage('Test') { 
            steps {
                // 
            }
        }
        stage('Deploy') { 
            steps {
                // 
            }
        }
    }
}
