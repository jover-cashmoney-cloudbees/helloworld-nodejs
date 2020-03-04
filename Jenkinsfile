pipeline {
  agent none
  stages {
    stage('Say Hello') {
      agent { label 'node-js' }
      steps {
        echo 'Hello World!'   
        sh 'java -version'
      }
    }
  }
}
