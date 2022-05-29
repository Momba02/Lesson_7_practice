properties([pipelineTriggers([pollSCM('* * * * *')])])
node{
    stage("clone"){
        git "https://github.com/Momba02/Lesson_7_practice.git"
    }
    stage("show files"){
        sh "ls -l"
    }
}
