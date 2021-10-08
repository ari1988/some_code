pipeline {
  agent any
  triggers {
    cron('H/15 * * * *')
}
  stages {
    stage('echo') {
      steps {
        echo 'hello from the trigger'
        echo 'hello again'
      }
    }

    stage('echo1') {
      steps {
        echo 'test'
      }
    }

  }
}
