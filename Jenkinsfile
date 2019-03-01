node {
    environment {
        env.HELLO = 'Hello World'
    }

    stage('Example') {
        echo $env.HELLO
        
        if (env.BRANCH_NAME == 'master') {
            echo 'I only execute on the master branch'
        } else {
            echo 'I execute else where'
        }
    }
}