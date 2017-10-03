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
        touch(file: 'LisaPipelineTest', timestamp: -1)
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo Deploying now! '
      }
    }
  }
}