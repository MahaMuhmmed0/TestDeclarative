pipeline {
    agent any
  
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
            }
        }
        stage('Test') {
            steps {
                echo 'Test completed'
              //  sh "Test from sh"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy completed'
            }
        }
    }
}
