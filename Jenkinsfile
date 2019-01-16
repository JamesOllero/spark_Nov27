pipeline {
  agent any
  stages {
    stage('First Step') {
      steps {
        echo 'Hello, World!'
      }
    }
    stage('Maven Build') {
      steps {
        sh 'mvn clean package -Dskiptests'
      }
    }
  }
}