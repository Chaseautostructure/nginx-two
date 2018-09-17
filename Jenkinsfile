pipeline {
  agent any
  stages {
    stage('My1Stage') {
      parallel {
        stage('My1Stage') {
          steps {
            echo 'This is my 1st stage. All it does is print this message.'
          }
        }
        stage('My2Stage') {
          steps {
            echo 'This is my 2nd stage. All it does is print this message.'
          }
        }
      }
    }
    stage('Stage1.2') {
      steps {
        echo 'This is stage 1.2'
      }
    }
  }
}