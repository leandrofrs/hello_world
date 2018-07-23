pipeline {
  agent any
  stages {
    stage('Bluid') {
      steps {
        sh 'echo test'
        sh 'echo "test 2"'
      }
    }
    stage('test') {
      steps {
        sh 'echo "test testing"'
      }
    }
  }
  environment {
    Name = 'Fred Flinstone'
  }
}