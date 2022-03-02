pipeline {
  agent { label 'rhelagent' 
  }
  stages {
    stage ('Download') {
      steps {
        sh '''
      sudo docker run -d -it --rm --name my-maven-project -v "$(pwd)":/home/ec2-user/workspace/pipelinprueba -w /home/ec2-user/workspace/pipelinprueba maven:3.3-jdk-8 mvn clean install
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
