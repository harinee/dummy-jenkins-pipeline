pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Unit tests') {
            steps {
                echo 'unit test'
            }
        }
        stage('Integration tests') {
            steps {
                echo 'integration test'
            }
        }
        stage('Package') {
            steps {
                echo 'package'
            }
        }
        stage('Deploy test env') {
            steps {
                echo 'Test env'
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
