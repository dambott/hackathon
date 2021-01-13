pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Starting Hackathon Build'
        cd distributed-tracing/go-app
        go build
      }
    }

  }
}
