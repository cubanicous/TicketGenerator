pipeline {
  agent any
  tools {
      maven 'M3'
  }
     stages {
     stage("Compile"){
              steps {
                   sh "mvn compile"
              }
              }
      stage("Unit test"){
          steps {
                 sh "mvn test"
          }
      }
     }
     }
