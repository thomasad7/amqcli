pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        echo '${env.ANT_HOME}'
        bat '${env.ANT_HOME}\bin\ant create_run_jar'
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
