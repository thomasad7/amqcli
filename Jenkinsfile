pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
        echo "JAVA_HOME = %JAVA_HOME%"
        echo "ANT_HOME = %ANT_HOME%"
        //bat "%ANT_HOME%/bin/ant.bat create_run_jar"
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
