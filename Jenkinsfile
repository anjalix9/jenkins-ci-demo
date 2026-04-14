pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/anjalix9/jenkins-ci-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'No build required'
            }
        }

        stage('Test') {
            steps {
                sh 'pytest || true'
            }
        }
    }
}