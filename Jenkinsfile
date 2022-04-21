pipeline {
  agent {
    docker {
      image 'python:alpine3.15'
    }

  }
  stages {
    stage('Tests') {
      steps {
        sh 'python -m unittest discover'
      }
    }

  }
}