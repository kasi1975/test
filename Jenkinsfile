pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh 'kasi.sh'
        echo 'all set'
        sleep 60
      }
    }
    stage('test') {
      steps {
        echo 'stage 2'
      }
    }
  }
}