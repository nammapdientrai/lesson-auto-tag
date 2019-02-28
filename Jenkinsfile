node {
    stage('Stage 01') {
        try {
            echo 'Stage 01'
        }
        catch (exc) {
            echo 'Stage 01 error'
            throw
        }
    }

    stage('Stage 02') {
        try {
            echo 'Stage 02'
        }
        catch (exc) {
            echo 'Stage 2 error'
            throw
        }
    }
}