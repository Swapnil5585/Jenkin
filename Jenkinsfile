pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'it is okay'
      }
    }

    stage('build') {
      steps {
        sh 'pwd '
      }
    }

    stage('deploy') {
      steps {
        sleep 50
        echo 'sleep completed'
      }
    }

  }
}