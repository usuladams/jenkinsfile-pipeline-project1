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
                touch demo2.txt
                '''
            }
        }
        stage('run-python') {
            steps {
                echo 'Hello Python3 World-3'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }

        stage('build-java') {
            steps {
                echo 'Compiling the Java source code'
                sh 'javac Hello.java'
            }
        }
        stage('run-java') {
            steps {
                echo 'Running the compiled Java code.'
                sh 'java Hello'
            }
        }

    }
}
