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
        bat 'cd test-application && yarn test'
      }
    }

    stage('Publish') {
      steps {
        bat 'cd test-application && yarn build'
      }
    }

  }
}