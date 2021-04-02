pipeline {
  agent any
  stages {
    stage('hello') {
      steps {
        echo 'hello'
      }
    }

    stage('check file') {
      steps {
        fileExists 'Test-App.ps1'
      }
    }

    stage('run script') {
      steps {
        powershell(script: '.\\Test-App.ps1', returnStatus: true, returnStdout: true)
      }
    }

  }
}