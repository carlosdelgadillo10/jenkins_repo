pipeline {
  agent any
  stages {
    stage('Buzz build') {
      steps {
        sh './jenkins/build.sh'
      }
    }

    stage('Buzz Test') {
      steps {
        sh './jenkins/test-all.sh'
      }
    }

  }
}