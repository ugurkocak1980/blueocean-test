pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'Hello Suara and Feyza Kocak'
        mail(subject: 'Hello Nurguel', body: 'Namaz adami yolda koymaz', from: 'ugurkocak1980@gmail.com', to: 'nurguel.kocak@gmail.com')
        sh 'echo \'Hi Suara and Feyza\''
      }
    }

  }
}