pipeline {
    agent any

    stages {
        stage('create_empty_file') {
            steps {
                sh 'touch empty_file.txt'
            }
        }
        stage('run_hello') {
            steps {
                sh 'echo "Hello from Pipeline!"'
            }
        }
    }
}