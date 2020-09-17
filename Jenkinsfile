pipeline {
    agent { dockerfile true }

    stages {
        stage('Build') {
            steps {
                echo 'Hello World ...'
                sh 'node --version'
                sh 'npm install'
            }
        }
        stage('Testing') {
            steps {
                echo 'Testing ...'
                sh 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying ...'
            }
        }
    }
}
