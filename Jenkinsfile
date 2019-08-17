pipeline {
  agent any
  stages {
    stage('Check') {
      steps {
        kubernetesDeploy(secretName: 'default-token-x4brx', secretNamespace: 'default')
      }
    }
  }
}