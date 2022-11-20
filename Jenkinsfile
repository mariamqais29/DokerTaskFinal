pipeline {

  agent any
  
  stages {


    stage('Build Image') {
      steps {
        sh 'sudo docker build -t mariamqais/bitcoin-price:1.0 .'
      }
    }

    stage('Push Image') {
      steps {
	  sh 'sudo docker push mariamqais/bitcoin-price:1.0'
        }
      }
    }

    
}
