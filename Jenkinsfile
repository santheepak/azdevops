pipeline {
    agent any // Specifies that any available agent (machine/node) can run the pipeline
 
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                // Example shell command: sh 'make build'
            }
        }
 
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Example shell command: sh 'make check'
                // Example for publishing test results: junit 'reports/**/*.xml'
            }
        }
 
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Example shell command: sh 'make publish'
            }
        }
    }
}
