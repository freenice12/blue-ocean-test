pipeline {
  agent any
  stages {
    stage('init') {
      parallel {
        stage('init') {
          steps {
            sh '''pwd
ls -alt'''
          }
        }
        stage('init2') {
          steps {
            sh '''pwd
ls -alt'''
          }
        }
      }
    }
  }
}