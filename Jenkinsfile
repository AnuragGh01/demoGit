pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        echo 'mvn test'
      }
    }

    stage('Build') {
      steps {
        echo 'mvn install'
      }
    }

    stage('deploy_testServer') {
      steps {
        echo 'deploy test'
      }
    }

    stage('deploy_podServer') {
      steps {
        echo 'deploy prod'
      }
    }

  }
}