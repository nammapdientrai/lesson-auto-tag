node {
    stage('Stage 01') {
        environment {
            def NAME_TRUE = 'TRUE'
            def NAME_FALSE = 'FALSE'
        }
        echo "${NAME_TRUE}"
        echo "${NAME_FALSE}"

        if (env.NAME_TRUE == 'TRUE') {
            echo 'True'
        } else {
            echo 'False'
        }
    }
}