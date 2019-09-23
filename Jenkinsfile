pipeline {
  agent any
  stages {
    stage('22') {
      steps {
        sleep 5
      }
    }
    stage('test') {
      steps {
        sleep 5
      }
    }
    stage('') {
      steps {
        timestamps() {
          mail(subject: 'test pipeline', body: 'test', to: 'yude.li@accenture.com')
        }

      }
    }
  }
}