pipeline {
    agent {
        label 'worker'
    }
    stages { 
        stage("Build and Push") {  
            steps {
                sh '''
                   cd vote
                  
                '''
            }
        }
        stage("Deploy") {
            steps {
                sh '''
                   echo "Deploying using kubectl"
                '''
            }
        }
    }
}
