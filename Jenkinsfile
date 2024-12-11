pipeline {
  agent any
  stages {
    stage('Pull code') {
      steps {
        git(url: 'git@github.com:aditi-bisht027/pull-jenkins-code.git', branch: 'master', credentialsId: 'ID_token')
      }
    }

  }
}