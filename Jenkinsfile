properties([pipelineTriggers([pollSCM('* * * * * ')])])
node {
    stage("clone") {
        git "https://github.com/omerk14/MySoftware.git"
    }
    stage("show files"){
        bat "dir"
    }
}