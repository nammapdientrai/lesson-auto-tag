pipeline {
    agent any

    environment {
        VERSION = 0;
    }

    stages {
        stage ('Example') {
            steps {
                env.VERSION = sh(returnStdout: true, script: "cd /root/.jenkins/workspace/lession-auto-tag  | git tag -l")

                echo env.VERSION;
            }
        }
    }
}