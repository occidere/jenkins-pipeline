pipeline {
  agent none
  stages {
    stage('Pre-Build') {
      steps {
        sh '''timestamp=`date +"%Y-%m-%d %H:%M:%S"`

echo "${timestamp}"'''
      }
    }
  }
}