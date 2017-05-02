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
    stage('Deployed') {
      steps {
        sh 'Deploying'
      }
    }
  }
  environment {
    test = 'test'
  }
}