pipeline {
  agent {
    docker {
      LinuxAgent-New
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
