pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Testing the app'
        listAWSAccounts()
        s3Upload 'dbctestapp'
      }
    }
  }
}