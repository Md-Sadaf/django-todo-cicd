pipeline {
  agent any
  stages {
    stage('to-do') {
      steps {
        sh 'docker build . -t todo-app && docker run -p 8000:8000 -d todo-app'
      }
    }

  }
}