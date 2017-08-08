pipeline {
    agent any

    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE    = 'sqlite'
    }

    stages {
        stage('Build') {
            steps {
                sh 'printenv'
            }
        }
    }
    post {
    failure {
        mail to: 'longislandjoe@gmail.com',
             subject: "Failed Pipeline: ${currentBuild.fullDisplayName}",
             body: "Something is wrong with ${env.BUILD_URL}"
    }
     success {
        mail to: 'longislandjoe@gmail.com',
             subject: "Success Pipeline: ${currentBuild.fullDisplayName}",
             body: "Good Job ${env.BUILD_URL}"
    }
}
}
