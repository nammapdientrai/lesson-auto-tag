pipeline {
    agent any

    stages {
        stage ('Example') {
            steps {
                sh 'sudo cd /root/.jenkins/workspace/lession-auto-tag  && git tag -l'
            }
        }
    }
}