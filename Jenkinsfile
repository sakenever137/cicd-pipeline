pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/sakenever137/cicd-pipeline.git', branch: 'test')
      }
    }

    stage('Build') {
      steps {
        build 'scripts scripts/build.sh'
      }
    }

  }
}