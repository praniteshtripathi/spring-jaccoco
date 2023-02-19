pipeline {
  agent any
  stages {

   stage ('clean') {
      steps {
        sh ./gradlew clean
      }
    }

    stage ('Build') {
      steps {
        sh 'echo Hello Build stage'
      }
    }
    stage ('Test') {
      steps {
        sh 'echo hello Test stage'
        
      }
    }
    stage ('development') {
      steps {
        sh 'echo hello Test stage'
        
      }
    }
  }
}