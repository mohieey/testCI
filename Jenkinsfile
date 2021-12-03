pipeline {
  agent any
  stages {
    stage('step1') {
      environment {
        DEMO = 'World'
      }
      steps {
        sh 'echo "Hello $DEMO"'
      }
    }

  }
}