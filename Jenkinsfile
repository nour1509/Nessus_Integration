pipeline {
    agent any 
    stages {
        stage('Version') {
            steps { 
                sh 'python3 --version'
            }
        }
        stage('Integration') {
            steps {
                sh 'python3 nour.py'
            }
        }
    }
}

