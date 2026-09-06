pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                git 'https://github.com/elamparithita2024-cloud/python-calculator.git'
            }
        }

        stage('Build') {
            steps {
                bat 'python calculator.py'
            }
        }
    }
}
