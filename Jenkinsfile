pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/SidduReddy03/Python_project.git'
            }
        }
        stage('Build') {
            steps {
                bat 'python3 math.py'
            }
        }
        stage('Test') {
            steps {
                bat 'python3 -m pytest'
            }
        }
    }
}
