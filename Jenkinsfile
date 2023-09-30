pipeline {
  agent any
  stages {
    stage('to-do') {
      steps {
        sh 'sudo -S docker build . -t todo-app && sudo -S docker run -p 8000:8000 -d todo-app'
      }
    }

  }
}