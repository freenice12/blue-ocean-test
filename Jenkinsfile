pipeline {
  agent any
  stages {
    stage('init') {
      parallel {
        stage('init') {
          steps {
            sh 'pwd'
          }
        }
        stage('init2') {
          steps {
            sh 'ls -alt'
          }
        }
      }
    }
  }
}