pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/renatorrocha/semantic-release-golang', branch: 'main')
      }
    }

    stage('Build') {
      steps {
        sh 'go mod tiddy'
        sh 'go build -o server src/main.go  '
      }
    }

  }
}