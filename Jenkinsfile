pipeline {
  agent {
    docker {
      args '-p 3001:3001'
      image 'node:9.4.0-alpine'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }

  }
}