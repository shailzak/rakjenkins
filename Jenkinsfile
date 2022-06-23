pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh 'echo "this is build stage"'
          }
        }

        stage('Test') {
          steps {
            sh 'echo "this is test stage"'
          }
        }

      }
    }

  }
}