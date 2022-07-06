//pipeline {
//agent any

//stages {

//    stage('TEST1') {
//      steps {
//        echo 'TEST1'
//      }
//    }

//    stage('TEST2') {
//      steps {
//        echo 'TEST2'
//        emailext body: 'TEST', subject: 'TEST', to: 'phani@hyd.com'
//        build job: 'roboshop--ansible', parameters: [string(name: 'COMPONENT', value: 'frontend')]
//      }
//    }

//  }

//  post {
//    fixed {
//      echo "Hello"
//           }
//    failure {
//      echo "Failed State"
//      emailext body: 'TEST', subject: 'TEST', to: 'phani@hyd.com'
//    }
//    cleanup {
//      echo "Common steps"
//    }
//  }

//}


pipeline {
  agent any

  environment {
    SAMPLE_URL="google.com"
  }

stages {

  stage("One") {
    steps {
      echo "URL = ${SAMPLE_URL}"
      echo SAMPLE_URL
      }
    }
    
  }
}