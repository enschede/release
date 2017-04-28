pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sleep 5
        sh './mvnw clean install'
        sh './mvnw release:prepare release:perform'
      }
    }
  }
}