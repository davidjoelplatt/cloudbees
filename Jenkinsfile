pipeline {
  agent any
  stages {
    stage('error') {
      parallel {
        stage('error') {
          steps {
            echo 'Give Me A Break'
          }
        }
        stage('ShellScript1') {
          steps {
            sh '''#!/bin/bash
java -version
uname -a'''
          }
        }
      }
    }
  }
}