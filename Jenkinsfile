pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo "This is build $BUILD_NUMBER for demo $demo"
      }
    }

  }
  environment {
    demo = '1'
  }
}
