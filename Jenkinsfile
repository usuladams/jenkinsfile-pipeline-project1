pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'echo Integrating Jenkins Pipeline with GitHub Webhook using Jenkinsfile'
            }
        }
        stage('run') {
            steps {
                echo 'Hello World'
                sh 'ls'
                sh 'pwd'
                sh '''
                whoami
                touch demo.txt
                '''
            }
        }
        stage('run-python') {
            steps {
                echo 'Hello Python3 World'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }

    }
}
