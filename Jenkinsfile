pipeline {
  agent any
  stages {
    stage('hello') {
      steps {
        echo 'hello'
      }
    }

    stage('test -f') {
      steps {
        fileExists 'Test-App.ps1'
      }
    }

  }
}