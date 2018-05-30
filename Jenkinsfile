pipeline {
  agent any
  stages {
    stage('download repositorio fron') {
      steps {
        sh 'git clone https://github.com/DiocesanInc/diocesan-eva-fe.git /home/ubuntu/diocesan-docker-container/'
        sh 'mv /home/ubuntu/diocesan-docker-container/diocesan-eva-fe home/ubuntu/diocesan-docker-container/app-frontend'
      }
    }
    stage('download repositorio back') {
      steps {
        sh 'git clone https://github.com/DiocesanInc/diocesan-api.git /home/ubuntu/diocesan-docker-container/'
        sh 'mv /home/ubuntu/diocesan-docker-container/diocesan-api home/ubuntu/diocesan-docker-container/app-backend'
      }
    }
  }
}
