pipeline {
  agent {
    docker {
      image 'golang:1.7'
    }
    
  }
  stages {
    stage('test') {
      steps {
        sh 'echo ${PWD} && ls -al'
      }
    }
  }
}