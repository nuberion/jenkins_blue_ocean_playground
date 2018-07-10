pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        tool(type: 'Maven', name: 'Maven3.5.4')
        sh 'mvn clean verify'
      }
    }
  }
}