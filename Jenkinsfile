pipeline {
    agent {
        label 'slave1'
    }

    stages {
        stage('code-checkout') {
            steps {
                git branch: 'main', credentialsId: 'GitHub', url: 'https://github.com/Bhanu-Ganga-DevOPs/randomjokes-nodejs-docker-proj.git'
            }
        }
    }

    stages {
        stage('build') {
            steps {
                git branch: 'main', credentialsId: 'GitHub', url: 'https://github.com/Bhanu-Ganga-DevOPs/randomjokes-nodejs-docker-proj.git'
            }
        }
    }
}