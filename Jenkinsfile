pipeline {
    agent any
    // { label 'master' }
    stages {
    stage ('Clone') {
                steps{
            git url: 'https://github.com/Avanishpatel/account-address-service.git'
                 }
            }
       stage('Build') {
          steps {
             sh 'gradle clean compileJava'
             sh './gradlew clean build'
          }
       }
    }
}