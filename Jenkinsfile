pipeline {
  agent any
  stages {
    stage('hello') {
      steps {
        echo 'hello'
      }
    }

    stage('cat') {
      steps {
        sh 'cat Test-App.ps1'
      }
    }

  }
}