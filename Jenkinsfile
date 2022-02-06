pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        withAnt(installation: 'Ant') {
          ant create_run_jar'
        }
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
