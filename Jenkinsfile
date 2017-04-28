pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sleep 5
        sh 'mvn clean install'
      }
    }
  }
}