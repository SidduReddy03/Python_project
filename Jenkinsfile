pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'master', url: 'https://github.com/SidduReddy03/Python_project.git'
            }
        }

        stage('Build') {
            steps {
                sh 'python3 math.py'
            }
        }

        stage('Test') {
            steps {
                sh 'python3 -m pytest'
            }
        }
    }
}