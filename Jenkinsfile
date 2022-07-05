pipeline {
  agent any

  stages {

    stage('TEST1') {
      steps {
        echo 'TEST1'
      }
    }

    stage('TEST2') {
      steps {
        echo 'TEST2'
      }
    }

  }

  post {
    fixed {
      echo "Hello"
           }
    failure {
      echo "Failed State"
    }
    cleanup {
      echo "Common steps"
    }
  }

}

