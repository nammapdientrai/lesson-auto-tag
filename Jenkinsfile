node {
    withEnv(['HELLO = world']) {
        echo '$HELLO'
    }

    stage('Example') {
        if (env.BRANCH_NAME == 'master') {
            echo 'I only execute on the master branch'

            echo '${env.BRANCH_NAME}'
        } else {
            echo 'I execute else where'
        }
    }
}