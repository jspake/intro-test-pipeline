pipeline {
  agent any
  stages {
    stage('Say hello') {
      steps {
        echo 'Hello ${MY_NAME}!'
        sh 'go version'
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}