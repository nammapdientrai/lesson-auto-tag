node {
    environment {
        BRANCH_NAME = 'master'
    }

    stage('Example') {
        echo BRANCH_NAME

        if (BRANCH_NAME == 'master') {
            echo 'I only execute on the master branch'
        } else {
            echo 'I execute elsewhere'
        }
    }
}