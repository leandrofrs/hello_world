pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo test'
            sh 'echo "test 2"'
          }
        }
        stage('Build2') {
          steps {
            sh 'echo "Build 2"'
          }
        }
      }
    }
    stage('test') {
      steps {
        sh 'echo "test testing"'
      }
    }
  }
  post {
    always {
      sh "Leandro, o Grande!"
    }
  }
  environment {
    Name = 'Fred Flinstone'
  }
}
