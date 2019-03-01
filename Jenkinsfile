node {
    stage ("Foo") {
        def data = new groovy.json.JsonSlurper().parseText(readFile('somefile.txt'))
        sh "make $(data.options)"
    }

    stage ("Bar") {
        try {
            sh = "Make"
        } catch (err) {
            slackSend message: "Oh dude, didn't workout. ${err}"
            error "Things wnt wrong"
        }
    }

    if (env.BRANCH_NAME == 'master') {
        stage ("Bar") {
            echo "Deloy !!!"
        }
    }
}