#!groovy

pipeline {
  agent none
  stages {
    stage('Maven Install') {
      agent {
        docker {
          image 'ubuntu:15.04'
        }
      }
      steps {
        sh 'mvn clean install'
      }
    } 
  }
}
