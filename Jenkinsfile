pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/nidhi4711/ci_cd_pipeline.git', branch: 'new-pipe'
            }
        }
        stage('Build') {
            steps {
                bat 'echo Building the project......'
            }
        }
        stage('Test') {
            steps {
                bat 'echo Running tests......'
            }
        }
        stage('Deploy') {
            steps {
                bat 'echo Deploying the project......'
            }
        }
    }
}
