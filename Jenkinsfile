pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        bat 'mvn clean compile test'
      }
    }
    stage('Build') {
      steps {
        bat 'mvn package'
      }
    }

  }
}
