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
        bat(script: 'python D:\\slave\\workspace\\demo_master\\1.py', returnStatus: true, returnStdout: true)
      }
    }

  }
}