pipeline {
  agent any 
  stages {
    stage('Static Code Analysis') { // Get code
      steps {
        // get code from our Git repository
        git 'https://github.com/balabt20/DevOps-Demo-WebApp.git'
      }
    }
    stage('Build') {
      steps {
        // run Gradle to execute compile and unit testing
        sh 'gradle clean compileJava test'
      }
    }
  }
}
