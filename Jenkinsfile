pipeline {
  agent any
  stages {
    stage('Docker') {
      steps {
        emailext(subject: 'Test123', body: 'This is a test', from: 'nick.macioce@davita.com', to: 'ndmacioce@gmail.com')
      }
    }
  }
}