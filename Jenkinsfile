pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                script {
                    echo "Branch: new-pipe"
                    sh "git branch"
                }
                git url: 'https://github.com/nidhi4711/ci_cd_pipeline.git', branch: 'new-pipe'
            }
        }
        // Other stages...
    }
}
