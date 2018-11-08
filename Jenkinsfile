stage 'checkout'
git "https://github.com/CarlosLlano/Jenkins.git"

stage 'build'
sh 'mvn clean package'

stage 'archive'
archiveArtifacts 'target/*.war'