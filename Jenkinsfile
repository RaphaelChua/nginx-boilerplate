pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'cd test-application && yarn install', label: 'Yarn install')
      }
    }

    stage('Test') {
      steps {
        bat 'yarn test'
      }
    }

  }
}