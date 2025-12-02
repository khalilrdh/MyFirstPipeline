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
    stage('Hello') {
      steps {
        echo 'Hello from GitHub Jenkinsfile'
      }
    }
  }
}
