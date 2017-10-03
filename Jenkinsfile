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
        touch 'LisaPipelineTest'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo Deploying now! '
      }
    }
  }
}