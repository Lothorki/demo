pipeline {
  agent {
    node {
      label 'demo'
    }

  }
  stages {
    stage('build') {
      steps {
        git(url: 'https://github.com/Lothorki/demo.git', branch: 'master', changelog: true)
      }
    }

  }
}