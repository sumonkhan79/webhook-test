pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh '''
                whoami
                source /etc/profile
                python --version
                '''
            }
        }
    }
}
