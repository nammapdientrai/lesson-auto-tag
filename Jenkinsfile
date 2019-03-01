pipeline {
    agent any

    environment {
        VERSION = 0;
    }

    stages {
        stage ('Example') {
            steps {
                script {
                    env.VERSION = sh(returnStdout: true, script: "sudo su && cd /root/.jenkins/workspace/lession-auto-tag  && git tag -l")
                }

                echo env.VERSION;
            }
        }
    }
}