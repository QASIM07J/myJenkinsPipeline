pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/YourUsername/JenkinsPipeline.git'
            }
        }
        stage('Install') {
            steps {
                sh 'npm install'
            }
        }
        stage('Test') {
            steps {
                sh 'npm test'
            }
        }
        stage('Build') {
            steps {
                sh 'npm run build'
            }
        }
    }
}
