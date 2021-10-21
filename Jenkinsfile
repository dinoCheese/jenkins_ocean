pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'hello'
      }
    }

    stage('Testing') {
      parallel {
        stage('Testing') {
          steps {
            sh 'python --version'
          }
        }

        stage('Test1') {
          steps {
            echo 'test'
          }
        }

      }
    }

  }
}