pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'go mod tiddy'
        sh 'go build -o server src/main.go  '
      }
    }

  }
}