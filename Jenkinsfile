pipeline {
  agent any
  stages {
    stage('s01') {
      parallel {
        stage('s01') {
          steps {
            sh 'echo "hello world"'
          }
        }

        stage('sp01') {
          steps {
            sh 'echo "welcome to parallel space"'
          }
        }

        stage('sp02') {
          steps {
            sh 'echo "parallel 02"'
          }
        }

      }
    }

  }
}