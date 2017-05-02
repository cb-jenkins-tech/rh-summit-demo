pipeline {
  agent none
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
}