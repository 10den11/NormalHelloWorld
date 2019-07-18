pipeline {
  agent any
  stages {
    stage('JUnit Tests') {
      steps {
        junit '/target/surefire-reports/*.xml'
      }
    }
  }
}