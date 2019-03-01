node {
    stage('Stage 01') {
        environment {
            NAME_TRUE = 'TRUE'
            NAME_FALSE = 'FALSE'
        }
        echo env.NAME_TRUE
        echo env.NAME_FALSE
        
        if (env.NAME_TRUE == 'TRUE') {
            echo 'True'
        } else {
            echo 'False'
        }
    }
}