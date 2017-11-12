pipeline {
  agent any
  stages {
    stage('Clone') {
      agent any
      steps {
        echo 'Hello clone'
      }
    }
    stage('Shell') {
      steps {
        sh 'echo "Hello from shell"'
      }
    }
  }
}