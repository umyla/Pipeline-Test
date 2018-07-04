pipeline {
  agent any
  stages {
    stage('Server1') {
      parallel {
        stage('Server1') {
          steps {
            echo 'QA  Server'
          }
        }
        stage('Server1a') {
          steps {
            echo 'QA Server2'
          }
        }
      }
    }
    stage('Server2') {
      parallel {
        stage('Server2') {
          steps {
            echo 'Prod Server'
          }
        }
        stage('Server2a') {
          steps {
            echo 'Server 2a'
          }
        }
      }
    }
  }
}