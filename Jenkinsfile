pipeline {
    agent {
        docker {
            image 'node:lts-buster-slim' 
            args '-p 0.0.0.0:3000:3000' 
        }
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
}
