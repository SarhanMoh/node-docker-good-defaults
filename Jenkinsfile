pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'https://github.com/SarhanMoh/node-docker-good-defaults', branch: 'main', changelog: true, poll: true)
      }
    }

  }
}