node {
    environment {
        env.HELLO = 'Hello World'
    }

    stage('Example') {
        if (env.BRANCH_NAME == 'master') {
            echo 'I only execute on the master branch'

            echo '${env.HELLO}'
        } else {
            echo 'I execute else where'
        }
    }
}