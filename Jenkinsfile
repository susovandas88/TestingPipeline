pipeline {
  agent any
  stages {
    stage('Pre-Build') {
      steps {
        git(url: 'https://github.com/susovandas88/TestingPipeline', branch: 'TestingPipeline', credentialsId: 'susovandas88')
      }
    }

  }
}