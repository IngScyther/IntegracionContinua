pipeline {
  agent any
  stages {
    stage('git pull') {
      steps {
        git(branch: 'master', url: 'https://github.com/IngScyther/IntegracionContinua.git')
      }
    }
    stage('build') {
      steps {
        sh 'gradle build'
      }
    }
  }
}