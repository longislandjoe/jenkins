pipeline {
    agent any 

    stages {
        stage('Build') { 
            steps { 
                sh 'curl http://www.google.com' 
            }
        }
        stage('Test'){
            steps {
                sh 'ls -lart'
                
            }
        }
        stage('Deploy') {
            steps {
                sh 'ls -l'
            }
        }
    }
}
