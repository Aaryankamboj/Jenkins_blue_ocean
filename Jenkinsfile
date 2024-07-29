pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''date
uptime
'''
        echo 'Building done'
      }
    }

    stage('Test') {
      environment {
        city = 'Gurugram'
      }
      steps {
        sleep 3
        echo 'Testing completed '
        sh 'echo $NAME'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Ended'
      }
    }

  }
}
