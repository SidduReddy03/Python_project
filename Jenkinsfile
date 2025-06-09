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
                bat 'echo Building project...' // or your actual build command
            }
        }
        stage('Test') {
            steps {
                bat 'echo Running tests...' // your test command here
            }
        }
    }
}
