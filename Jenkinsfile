pipeline {
  agent any
  stages {
    stage('stag1') {
      steps {
        echo "This is build ${BUILD_NUMBER} of demo ${DEMO}"
      }
    }

  }
  environment {
    DEMO = '1'
  }
}
