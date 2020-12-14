pipeline {
  agent {
    label "LinuxAgent-New"
        }
  stages {
    stage('Build') {
      steps {
        sh 'npm install'
      }
    }
     stage('Test') {
            steps {
                sh './jenkins/scripts/test.sh'
            }
        }

  }
}
