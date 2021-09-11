pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        echo 'Hello. World!'
      }
    }

    stage('error') {
      steps {
        pwd()
      }
    }

  }
}