pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        echo 'hello from the trigger again'
        echo 'hello again'
      }
    }

  }
  triggers {
    cron('H/15 * * * *')
  }
}