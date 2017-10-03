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
        jiraSearch 'project = "GTS SWES 2017" and issuetype = Triage and status = Open'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo Deploying now! '
      }
    }
  }
}