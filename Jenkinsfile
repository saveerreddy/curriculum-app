pipeline {
  agent any
  stages {
    stage('checkout-code') {
      steps {
        git(url: 'https://github.com/saveerreddy/curriculum-app.git', branch: 'dev')
        sh 'ls -lh'
      }
    }

  }
}