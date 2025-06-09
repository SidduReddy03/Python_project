pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
            checkout([$class: 'gitSCM', branches:[[name: 'master'] extensions: [], userRemoteConfigs: [[url: 'https://github.com/SidduReddy03/Python_project.git'])
            }
        }
        stage('build') {
            steps {
            gitbranch: 'master', url: 'https://github.com/SidduReddy03/Python_project.git'
            sh 'python3 math.py'
            }
        }
        stage('test') {
            steps {
            sh 'python3 -m pytest'
            }
        }
    }
}
