pipeline {
  agent {
    dockerfile true
  }
  stages {
    stage('Pre-Build') {
      steps {
        echo 'Building docker file'
      }
    }

  }
  environment {
    Env = 'dev'
  }
}
