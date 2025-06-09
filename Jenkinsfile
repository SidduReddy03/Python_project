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
                bat 'python math.py'
            }
        }
        stage('Test') {
            steps {
                bat 'python -m test_math.py'
            }
        }
    }
}
