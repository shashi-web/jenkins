pipeline {
 agent any
 stages {
  stage('Hello') {
   steps {
    sh 'hostname'
   }
  post {
          success {
              echo 'Hostname of agent running'
          }
      }
  post {
          failure {
              echo 'check the code'
          }
      }
  }

  stage('hello2') {
   steps {
    sh 'echo hello world 2'
   }
  }
 }
}