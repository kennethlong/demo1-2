pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'Hello Kenny!  Build number is $BUILD_NUMBER DEMO is $DEMO'
      }
    }
  }
  environment {
    DEMO = '1'
  }
}
