node{
    stage 'checkout'
    checkout scm //git repostory configured outside this script

    stage 'build'
    sh 'mvn clean package' //maven build

    stage 'archive'
    archiveArtifacts 'target/*.war' //archive .war for build history
}