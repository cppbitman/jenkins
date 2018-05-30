#!/usr/bin/env groovy
// Declarative //
pipeline {
  agent any //allocate executor and workspace for the pipeline
  stages {
    stage('Build') {
      steps {
        echo 'Building..'
      }
    }
    stage('Test') {
      steps {
        echo 'Testing..'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploying....'
      }
    }
  }
}
// Script //
node {
  stage('Build') {
    echo 'Script Building....'
  }
  stage('Test') {
    echo 'Script Testing....'
  }
  stage('Deploy') {
    echo 'Script Deploying....'
  }
}
