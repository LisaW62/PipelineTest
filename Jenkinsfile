pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'Initialize step'
      }
    }
    stage('build') {
      steps {
        pwd()
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo Deploying now! '
      }
    }
  }
}