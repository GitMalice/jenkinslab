node {
  stage('SCM checkout') {
    git 'https://github.com/GitMalice/jenkinslab'
    }
  stage('compile package') [
    sh 'mvn package'
    }
}
