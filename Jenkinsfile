pipeline{
  agent any{
    tools{
      maven 'Maven'
    }
    stages{
      stage('Checkout'){
        steps{
          sh 'https://github.com/Ranjana2225/maven-ranjana1.git'
        }
      }
      stage('compile'){
        steps{
          sh 'mvn compile'
        }
      }
      stage('Test'){
        steps{
          sh 'mvn clean install'
        }
      }
      stage('package'){
        steps{
          sh 'mvn package'
        }
      }
    }
  }
