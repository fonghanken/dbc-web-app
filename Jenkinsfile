pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'Testing the app'
        s3Upload 'dbctestapp'
      }
    }
  }
}