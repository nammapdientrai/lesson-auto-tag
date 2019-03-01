pipeline {
    agent any

    environment {
        VERSION = 0;
    }

    stages {
        stage ('Example') {
            steps {
                script {
                    env.VERSION = version sh(returnStdout: true, script: "git tag -l")
                }

                echo env.VERSION;
            }
        }
    }
}