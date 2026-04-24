node {
  stage('SCM checkout') {
    git branch: 'main', url: 'https://github.com/GitMalice/jenkinslab'
  }
  stage('compile package') {
    // get maven home path
    def mvnHome = tool name: 'maven-3', type: 'maven'
    sh "${mvnHome}/bin/mvn package" //using interpolation we use double quotes !!!
  }
}
