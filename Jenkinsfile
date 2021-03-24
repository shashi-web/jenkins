pipeline {
 agent {
 label 'Ansible'
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