pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'javac T2.java'
      }
    }
    stage('run') {
      steps {
        sh 'java T2'
      }
    }
    stage('print') {
      steps {
        echo 'cry test'
      }
    }
  }
}