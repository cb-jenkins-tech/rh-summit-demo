pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''echo build
'''
      }
    }
    stage('Test') {
      steps {
        echo 'test'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }
  }
  environment {
    test = 'test'
  }
}