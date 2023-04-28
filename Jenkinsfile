pipeline {
  agent any
 
  stages {
    stage('Clone') {
      steps {
        git ' https://github.com/saritaaaaaaa/node-js-sample.git'
      }
    }
    stage('Test') {
      steps {
        sh 'npm install'
        sh 'npm test'
      }
    }
