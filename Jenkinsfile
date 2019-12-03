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
        sh './var/lib/jenkins/workspace/Test-b_master/script.sh'
      }
    }

  }
}