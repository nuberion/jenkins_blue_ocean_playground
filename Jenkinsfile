pipeline {
  agent any
  stages {
    stage('Compile') {
      steps {
        echo 'Stage: Compile'
        echo 'WORKSPACE: $WORKSPACE'
        echo 'PATH: $PATH'
        tool(type: 'jdk', name: 'Java8u172')
        tool(type: 'maven', name: 'Maven3.5.4')
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