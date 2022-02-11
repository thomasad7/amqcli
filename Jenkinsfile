pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        bat '%ANT_HOME%/bin/ant all'
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
