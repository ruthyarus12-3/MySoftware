properties([pipelineTriggers([pollSCM('*/30 * * * *')])])
node {
    stage("clone"){
        git "https://github.com/ruthyarus12-3/MySoftware.git"
    }
    stage("show files"){
        sh "ls -l"
    }
}
