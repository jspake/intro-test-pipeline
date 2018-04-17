library 'SharedLibs'
pipeline {
  agent any
  stages {
    stage('Say hello') {
      steps {
        echo 'Hello WORLD!'
      }
    }
stage('Shared Lib') {
         steps {
             helloWorld("Jenkins")
         }
      }
  }
}
