pipeline {
  agent { label 'rhelagent' 
  }
  stages {
    stage ('Download') {
      steps {
        sh '''
        uname -a
        cat /etc/os-release
        ps -ef
        echo "Do something"
        docker ps
        '''
      }
    }
    stage ('Test') {
      steps {
        echo "Do something"
      }
    }
    stage ('Deploy') {
      steps {
        echo "Do something"
      }
    }
  }
}
