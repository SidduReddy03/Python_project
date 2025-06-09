pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
            checkout([$class: 'gitSCM', branches:[[name: 'main'] extensions: [], userRemoteConfigs: [[url: ])
            }
        }
        stage('build') {
            steps {
            gitbranch: 'main', url:
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
