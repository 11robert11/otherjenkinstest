pipeline {
  agent {
    node {
      label 'node:16.13.1-alpine'
    }

  }
  stages {
    stage('') {
      steps {
        sleep 5
        sh 'docker.build registry'
      }
    }

  }
}