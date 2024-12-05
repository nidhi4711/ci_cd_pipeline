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
                echo 'Building the project……'
            }
        }
        stage('Test') {
            steps {
                echo 'Run tests…'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying project…'
            }
        }
    }
}
