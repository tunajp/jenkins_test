pipeline {
  agent any
  stages {
    stage('first step') {
      steps {
        echo 'test first step'
      }
    }
    stage('second step') {
      steps {
        cleanWs()
      }
    }
  }
}