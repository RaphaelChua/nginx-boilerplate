pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat(script: 'yarn install C:\\Windows\\System32\\config\\systemprofile\\AppData\\Local\\Jenkins.jenkins\\workspace\\nginx_development_main\\test-application', label: 'Yarn install')
      }
    }

  }
}