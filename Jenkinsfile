pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
         //       sh 'ls'
                echo "Build"
            }
        }
        
        stage('Sanity check') {
            steps {
              //  input "Does the staging environment look ok?"
             //   sh 'ls'
                echo "Sanity"
            }
        }
        
        stage('Test') {
            steps {
          //      sh 'printenv'
                echo "Test"
            }
        }        
        
    }
    
}
