pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Getting code from GitHub'
            }
        }

        stage('Build') {
            steps {
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo 'Running Tests'
            }
        }

        stage('Deploy') {
            steps {
                sh 'cp index.html /tmp/index.html'
            }
        }
    }
}
