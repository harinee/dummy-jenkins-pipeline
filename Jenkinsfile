    pipeline {
       agent any
      stages {
        stage('Build ') {
          steps {
            echo 'build'
          }
        }
        stage('Unit tests') {
          steps {
           echo 'unit testing'
          }
        }
        stage('Integration tests') {
         steps {
          echo 'integration testing'
          }
        }
        stage('Deploy test env') {
          steps {
            echo 'Test env ready'
          }
        }
        stage('Functional tests') {
           steps {
             echo 'Functional tests'
           }
        }
        stage('Deploy staging') {
          steps {
            echo 'Staging ready'
          }
        }
    }
  }


