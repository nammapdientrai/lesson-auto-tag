pipeline {
    agent any

    environment {
        BRANCH_NAME = 'master'
    }

    stages {
        stage ('Example') {
            steps {
                echo env.BRANCH_NAME

                script {
                    if (env.BRANCH_NAME == 'master') {
                        echo 'I only execute on the master branch'
                    } else {
                        echo 'I execute elsewhere'
                    }
                }
            }
        }
    }
}