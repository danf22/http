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
}
}
