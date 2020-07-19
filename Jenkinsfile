pipeline {
    agent { dockerfile true }

    stages {
        stage('Build') {
            steps {
                echo 'Hello World ...'
                sh 'node --version'
                sh 'npm install'
                // sh 'docker-compose up -d'
                // sh 'docker-compose run app npm install'
            }
        }
        stage('Testing') {
            steps {
                echo 'Testing ...'
                sh 'npm test'
                // sh 'docker-compose run app npm test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying ...'
            }
        }
    }
}
