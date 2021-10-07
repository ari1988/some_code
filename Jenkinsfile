pipeline {
  agent any
  stages {
    stage('echo') {
      steps {
        echo 'hello from the trigger again'
        echo 'hello again'
      }
    }

    stage('echo1') {
      steps {
        echo 'test'
      }
    }

  }
  triggers {
    cron('H/15 * * * *')
  }
}