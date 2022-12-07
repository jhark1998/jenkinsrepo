pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sleep 9
        sh 'echo "this is my first test"'
        echo 'executing build stage'
      }
    }

  }
  environment {
    Name = 'Jenkinstest'
    Tag = '1.o.o'
  }
}