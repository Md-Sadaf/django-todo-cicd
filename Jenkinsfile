pipeline {
  agent any
  stages {
    stage('to-do') {
      steps {
        sh 'sudo su && sudo docker build . -t todo-app && sudo docker run -p 8000:8000 -d todo-app'
      }
    }

  }
}