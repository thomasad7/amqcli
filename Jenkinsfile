pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        bat 'ant create_run_jar'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}
