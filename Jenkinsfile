pipeline {
    agent { label 'linux }

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                sh 'ls -l'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying application...'
            }
        }
    }
}
