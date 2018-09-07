pipeline {
  agent any
  stages {
    stage('test') {
      parallel {
        stage('test') {
          steps {
            echo 'coucou'
          }
        }
        stage('') {
          steps {
            echo 'toto'
          }
        }
        stage('') {
          steps {
            echo 'titi'
          }
        }
      }
    }
    stage('') {
      steps {
        sleep 1
        echo 'popo'
      }
    }
  }
}