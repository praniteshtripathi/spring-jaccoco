pipeline {
  agent any
  stages {

   stage ('clean') {
      steps {
        script {
           sh ./gradlew clean build
        }
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
