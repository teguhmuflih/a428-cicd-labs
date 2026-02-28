pipeline {
    agent {
        docker {
            image 'dslim/docker-slim' 
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