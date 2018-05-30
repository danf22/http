pipeline {
  agent any
  stages {
    stage('Inicio') {
      steps {
        sh 'docker run -d  lephare/apache'
      }
    }
    stage('test2') {
      steps {
        echo 'nose2a'
      }
    }
  }
}
