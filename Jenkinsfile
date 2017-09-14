pipeline {
  agent any
  stages {
    stage('Preparation') {
      steps {
        sh 'echo tmp_dir'
      }
    }
  }
  environment {
    tmp_dir = '/tmp/speed_rel_deploy'
  }
}