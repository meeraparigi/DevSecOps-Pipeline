@Library("Shared") _
pipeline {
  agent any
  stages {
    stage('Msg') {
      steps {
        script {
           hello('Hello! are you scanning my branch jfrog-test?')
         } 
      }
    }
  }
}
