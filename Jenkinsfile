pipeline {
    agent {
        docker {
            image 'node:16-buster-slim' 
            args '-u root:root'  // Menggunakan args untuk set UID/GID jika perlu, tidak untuk port mapping.
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