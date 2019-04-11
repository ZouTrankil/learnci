pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('error') {
      steps {
        bat(script: 'echo hello', encoding: 'UTF-8', label: 'testEcho', returnStatus: true, returnStdout: true)
      }
    }
  }
}