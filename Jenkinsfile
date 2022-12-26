pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'python3 time.py'
      }
    }

    stage('Test') {
      steps {
        sh 'echo (\'Testing..\')'
      }
    }

  }
}