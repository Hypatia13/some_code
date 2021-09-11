pipeline {
  agent any
  triggers {
    cron(H/1 * * * *)
  }
  stages {
    stage('echo') {
      steps {
        echo 'Hello from the trigger!'
      }
    }
  }
}
