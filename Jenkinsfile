pipeline {
 agent {
   agent1 { label 'SHELL' }
 }
 stages {
  stage('Hello') {
   steps {
    sh 'hostname'
   }
  }
  stage('hello2') {
   steps {
    sh 'echo hello world 2'
   }
  }
 }
}