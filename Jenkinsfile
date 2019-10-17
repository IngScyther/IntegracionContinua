pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        git(url: 'https://github.com/IngScyther/IntegracionContinua.git', branch: 'master')
        sh 'gradle build'
      }
    }
  }
}