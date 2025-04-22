pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'go mod tidy'
        sh 'go build -o server src/main.go  '
      }
    }

  }
}