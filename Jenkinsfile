pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/saiabbhiram/webhooks-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Latest GitHub code downloaded!'
                sh 'ls -la'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
    }
}
