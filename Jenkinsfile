pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            sh 'echo $Pwd'
          }
        }

        stage('Test') {
          steps {
            echo 'Hello world'
          }
        }

      }
    }

  }
}