pipeline {
  agent {
    docker {
      image 'go-agent'
    }
    
  }
  stages {
    stage('fail-step') {
      steps {
        sh '/bin/false'
      }
    }
  }
}