pipeline {
  agent any
  stages {
    stage('Checkout Code') {
      steps {
        git 'https://github.com/spamyouracc-spec/pipeline.git'
      }
    }
    stage('Show Files') {
      steps {
        bat 'dir'   // Windows
        // sh 'ls -la'  // Linux/macOS
      }
    }
  }
}
