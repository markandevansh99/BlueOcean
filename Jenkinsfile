pipeline{
    agent any
    stages{
      stage('Build'){
          steps{
          echo 'Build Stage'
          }
      }
      stage('Test'){
          steps{
          bat 'mvn clean'
          }
      }
      stage('Clean'){
          steps{
          bat 'Clean Stage'
          }
      }
    }
}
