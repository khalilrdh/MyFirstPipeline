pipeline {
  agent any
  stages {
    stage('Hello') {
      steps {
        echo 'Hello World'
      }
    }
    
    stage('Date') {
      steps {
        sh 'date'
      }
    } 
    stage('Hi') {
      steps {
        echo 'Hello from GitHub Jenkinsfile'
      }
    }
  }
}
