node {
  stage('SCM checkout') {
    git branch: 'main', url: 'https://github.com/GitMalice/jenkinslab'
  }
  stage('compile package') {
    sh 'mvn package'
  }
}
