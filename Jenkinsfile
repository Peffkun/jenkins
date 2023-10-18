pipeline {
  agent any
  stages {
    stage('stage 1') {
      steps {
        sh '''if grep "$user" /etc/passwd > /dev/null
    

then
	echo "l\'utilisateur n\'existe pas"
    else
	echo "l\'utilisateur existe"
    fi'''
      }
    }

    stage('stage 2') {
      steps {
        sh 'mkdir F1'
      }
    }

  }
}