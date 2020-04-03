pipeline {
    agent any
    tools {nodejs "node"}
       stages {
          stage('Fetch') {
             git 'https://github.com/ogulcanarbc/postman-api-trial.git'
      }
          stage('Run') {
             sh 'npm install && npm run api-tests-ci-demo'
      }
     
    }
}
