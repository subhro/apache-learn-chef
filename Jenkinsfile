pipeline {
  agent {
    node {
      label 'apacheCookbookTest'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'kitchen verify'
      }
    }
  }
}
