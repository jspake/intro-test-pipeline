pipeline {
  agent any
  stages {
    stage('Say hello') {
      steps {
        echo 'Hello ${MY_NAME}!'
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}