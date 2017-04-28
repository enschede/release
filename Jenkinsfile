pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh './mvnw release:prepare release:perform'
      }
    }
  }
}