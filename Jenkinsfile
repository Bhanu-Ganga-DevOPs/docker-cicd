pipeline {
    agent  any

    stages {
        stage('code-checkout') {
            steps {
                git branch: 'main', credentialsId: 'GitHub', url: 'https://github.com/Bhanu-Ganga-DevOPs/randomjokes-nodejs-docker-proj.git'
            }
        }
    }
}