pipeline {
  agent any
  stages {
    stage('aa') {
      steps {
        sh 'echo hello'
      }
    }
    stage('Export Version') {
      steps {
        sh 'echo nello'
      }
    }
  }
  environment {
    KUBE_URL = credentials('KUBE_URL')
    KUBE_TOKEN = credentials('KUBE_TOKEN')
    DOCKER_URL = credentials('DOCKER_URL')
    DOCKER_USERNAME = credentials('DOCKER_USERNAME')
    DOCKER_PASSWORD = credentials('DOCKER_PASSWORD')
  }
}