pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'ls'
            }
        }
        
        stage('Sanity check') {
            steps {
              //  input "Does the staging environment look ok?"
                sh 'ls'
            }
        }
        
        stage('Test') {
            steps {
                sh 'printenv'
            }
        }        
        
    }
    
}
