#!groovy

properties([disableConcurrentBuilds()])

pipeline {
    agent {
        label 'master"
        }
  options {
        buildDiscarder(logRotator(numToKeepStr: '10', artifactNumToKeepStr: '10'))
        timestamps()
        }
        stages {
        stage("First step") {
        steps {
            sh 'ping mail.ru/" 
            }
        }
        stage("Second step") {
            steps {
                sh "ping https: // mtkp.bmstu.ru/"
                }
              }
          }
      }
