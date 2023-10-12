pipeline {
    agent any
    environment{
        NEW_VERSION='1.3.0'
    }
    stages {
        stage('SCM checkout') {
            steps {
                 echo 'Running from github'
                echo 'checkout completed'
            }
        }
        stage('Build') {
            steps {
                echo 'Build completed'
                echo "Version= $[NEW_VERSION]"
            }
        }
        stage('Test') {
            steps {
                echo 'Test completed'
                sh "$[NEW_VERSION]"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy completed'
            }
        }
    }
}
