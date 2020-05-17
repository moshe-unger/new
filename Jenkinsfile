properties([parameters([string(defaultValue: '31', description: '', name: 'NAME', trim: false)]), pipelineTriggers([pollSCM('* * * * *')])])
node {
    stage("clone"){
        git "https://github.com/moshe-unger/new.git"
    }
    stage("show"){
        sh "ls"
       // bat "dir"
    }
}
