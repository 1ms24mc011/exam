pipeline {
  agent any
  stages {

    stage ("checking version") {
      steps {
        sh 'python3 --version'
      }
  
    }

    stage ("running script") {
      steps {
        sh 'python3 hello.py'
      }
    }
  }
}
