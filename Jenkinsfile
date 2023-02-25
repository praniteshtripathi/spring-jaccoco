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
  }



