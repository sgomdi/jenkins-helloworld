pipeline {
  agent any
  stages {
    stage('verify version') {
      steps {
        sh 'node --version'
      }
    }
    stage('hello') {
      steps {
        sh 'php hello.php'
      }
    }
  }
}
