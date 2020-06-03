pipeline {
  agent any

  stages {
    stage('Verify Branch') {
      steps {
        echo "$GIT_BRANCH"
      }
      steps {
        sh(script: 'echo hello World')
      }
    }
  }
}
