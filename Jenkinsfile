pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        tool(type: 'jdk', name: 'Java8u172')
        tool(type: 'maven', name: 'Maven3.5.4')
        sh 'mvn clean verify'
      }
    }
  }
}