pipeline {
  agent any
  stages {
    stage('stag1') {
      steps {
        echo "This is build ${BUILD_NUMBER} of demo ${DEMO}"
        sh 'echo "This is build $BUILD_NUMBER for demo $DEMO"'
        sh 'echo "End of Job demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}