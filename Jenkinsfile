pipeline {
    agent any
    // { label 'master' }
    stages {
       stage('Build') {
          steps {
             sh './gradlew clean build'
          }
       }
    }
}