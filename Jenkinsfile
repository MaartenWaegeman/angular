pipeline {
  agent any
  stages {
    stage('Tests') {
      parallel {
        stage('Tests') {
          steps {
            sleep 15
          }
        }
        stage('Unit tests') {
          steps {
            sleep 15
          }
        }
        stage('Integration tests') {
          steps {
            sleep 15
            sleep 20
          }
        }
      }
    }
    stage('Dev') {
      steps {
        sleep 15
      }
    }
    stage('Staging') {
      steps {
        sleep 15
      }
    }
    stage('Production') {
      steps {
        sleep 15
      }
    }
  }
}