pipeline {
    agent any
    tools {nodejs "node"}
    stages {
         stage('Postman Api') {
          git 'https://github.com/ogulcanarbc/postman-api-trial.git'
          sh 'npm install'
          sh 'npm run api-tests-ci-demo'
   }
     
    }
}
