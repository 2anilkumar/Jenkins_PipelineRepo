pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        sh 'echo hello1'
      }
    }
    stage('testing') {
      steps {
        sh 'echo hello2'
      }
    }
    stage('deploy to QA') {
      steps {
        sh 'echo hello3'
      }
    }
    stage('system testing') {
      steps {
        sh 'echo hello4'
      }
    }
    stage('deploy to PROD') {
      steps {
        sh 'echo deployed to PROD'
      }
    }
  }
}