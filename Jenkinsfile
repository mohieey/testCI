pipeline {
  agent {
    docker {
      image "mongo"
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
        sh 'mongo --version'
      }
    }

  }
}