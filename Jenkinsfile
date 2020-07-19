pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World ...'
            }
        }
        stage('Testing') {
            steps {
                echo 'Testing ...'
                sh 'npm run test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying ...'
            }
        }
    }
}
