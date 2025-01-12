pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'Hello Selim'
        mail(subject: 'HelloNurgül', body: 'I love you Nurguel', from: 'ugurkocak1980@gmail.com', to: 'nurguel.kocak@gmail.com')
        sh 'echo \'Hi Suara and Feyza\''
      }
    }

  }
}