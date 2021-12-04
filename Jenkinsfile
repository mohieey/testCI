pipeline {
  agent {
    docker {
      image "node"
    }
  }
  stages {
    stage('step1') {
      environment {
        DEMO = 'World'
      }
      steps {
        sh 'echo "Hello $DEMO"'
        sh 'cat package.json'
        sh 'docker version'
      }
    }

  }
}