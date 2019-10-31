@Library('git_shared_library@master') _
pipeline {
agent any
stages{
  stage ('checkout') {
    steps {
        checkout scm
        docker_build()
        }
    }
  }
}
