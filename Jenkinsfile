node {
    environment {
        def HELLO = 'Hello World'
    }

    stage('Example') {
        echo "${HELLO}"
        
        if (env.BRANCH_NAME == 'master') {
            echo 'I only execute on the master branch'
        } else {
            echo 'I execute else where'
        }
    }
}