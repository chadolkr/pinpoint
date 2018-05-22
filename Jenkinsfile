pipeline {
  agent any
  stages {
    stage('s1') {
      parallel {
        stage('s1') {
          steps {
            echo 's1'
          }
        }
        stage('s2') {
          steps {
            echo 's2'
          }
        }
      }
    }
    stage('t1') {
      steps {
        echo 't1'
      }
    }
    stage('e') {
      steps {
        echo 'end'
      }
    }
  }
}