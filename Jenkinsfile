pipeline {
  agent any
  stages {
    stage('download fron') {
      steps {
        sh 'rm -rf /home/ubuntu/diocesan-docker-container/app-frontend'
        sh 'mkdir /home/ubuntu/diocesan-docker-container/app-frontend'
        sh 'git clone https://github.com/DiocesanInc/diocesan-eva-fe.git /home/ubuntu/diocesan-docker-container/app-frontend'
      }
    }
    stage('download back') {
      steps {
        sh 'rm -rf /home/ubuntu/diocesan-docker-container/app-backend'
        sh 'mkdir /home/ubuntu/diocesan-docker-container/app-backend'
        sh 'git clone https://github.com/DiocesanInc/diocesan-api.git /home/ubuntu/diocesan-docker-container/app-backend'
      }
    }
}
}
