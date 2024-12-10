pipeline {
    agent any
  
    stages {
        stage('Build') {
            steps {
                script {
                    // Build your Docker image
                     bat 'docker build -t my-nodejs-ápp.'
                }
            }
        }
        stage('Test') {
            steps {
                script (
                    // Run tests here if you have any echo 'Running tests.....
                     echo 'Running tests...'
                }
            }
        }        
stage('Deploy') {
    steps {
        script {
// Deploy your Docker image echo 'Deploying application...
          echo 'Deploying application...'
}}}}}
