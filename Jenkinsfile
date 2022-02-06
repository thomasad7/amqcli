pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        bat "%ANT_HOME%/bin/ant.bat create_run_jar"
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
