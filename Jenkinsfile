pipeline {
  agent any
  stages {
    stage('S3 Upload') {
      steps {
        s3Upload(consoleLogLevel: 'INFO', dontWaitForConcurrentBuildCompletion: true, entries: [[bucket: 'dbctestapp', excludedFile: '', flatten: false, gzipFiles: false, keepForever: false, managedArtifacts: false, noUploadOnFailure: false, selectedRegion: 'ap-southeast-1', showDirectlyInBrowser: false, sourceFile: '*', storageClass: 'STANDARD', uploadFromSlave: false, useServerSideEncryption: false]], pluginFailureResultConstraint: 'FAILURE', profileName: 'jenkinspublisher', userMetadata: [])
      }
    }
  }
}