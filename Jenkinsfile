pipeline {
  agent any
  stages {
    stage('first') {
      steps {
        echo 'hello '
      }
    }

    stage('second') {
      steps {
        echo 'hhh'
      }
    }

    stage('last') {
      steps {
        timeout(time: 7)
      }
    }

  }
}