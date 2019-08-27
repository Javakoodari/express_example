pipeline {
  agent any
  stages {
    stage('Docker build') {
      parallel {
        stage('Docker build') {
          steps {
            sh 'docker build -t webapp: $BUILD_NUMBER .'
          }
        }
        stage('Docker build 2') {
          steps {
            sh '''docker build -t webapp: $BUILD_NUMBER .
'''
          }
        }
      }
    }
  }
}