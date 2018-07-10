pipeline {
  agent any
  stages {
    stage('Setup') {
      steps {
        tool(type: 'jdk', name: 'Java8u172')
        tool(type: 'maven', name: 'Maven3.5.4')
      }
    }
    stage('Build') {
      steps {
        sh 'mvn clean verify'
      }
    }
  }
}