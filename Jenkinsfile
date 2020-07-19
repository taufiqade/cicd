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
                npm test
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying ...'
            }
        }
    }
}
