node {
    environment {
        NAME_TRUE = 'TRUE'
        NAME_FALSE = 'FALSE'
    }
    
    stage('Stage 01') {
        echo "${NAME_TRUE}"
        echo "${NAME_FALSE}"

        if (env.NAME_TRUE == 'TRUE') {
            echo 'True'
        } else {
            echo 'False'
        }
    }
}