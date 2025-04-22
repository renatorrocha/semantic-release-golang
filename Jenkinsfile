pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/renatorrocha/semantic-release-golang', branch: 'main')
      }
    }

  }
}