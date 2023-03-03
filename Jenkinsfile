pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        git(url: 'git@github.com:msedebay-git/devsecops-gitlab-java-vulnerable-application.git', branch: 'main')
      }
    }

  }
}