pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "------------ Build step ----------"'
      }
    }

    stage('Deploy') {
      steps {
        sh '''cd /var/lib/jenkins/workspace/Test-b_master/
chmod 777 script.sh
./script.sh'''
      }
    }

  }
}