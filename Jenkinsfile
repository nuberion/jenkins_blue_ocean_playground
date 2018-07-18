pipeline {
  agent any
  stages {
    stage('Compile') {
      agent any
      steps {
        echo 'Stage: Compile'
        sh 'printenv'
        tool(type: 'jdk', name: 'Java8u172')
        tool(type: 'maven', name: 'Maven3.5.4')
        sh 'printenv'
        sh 'mvn compile'
      }
    }
    stage('Test') {
      steps {
        echo 'Stage: Test'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Stage: Deploy'
      }
    }
  }
}