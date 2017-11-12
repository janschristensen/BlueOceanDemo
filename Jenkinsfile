pipeline {
  agent any
  stages {
    stage('Clone') {
      steps {
        git(url: 'https://github.com/janschristensen/BlueOceanDemoRepo2.git', branch: 'master', credentialsId: 'jan')
      }
    }
  }
}