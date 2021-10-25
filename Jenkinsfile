pipeline {
  agent any
  stages {
    stage('myStage'){
      steps {
        bat 'mvn clean' 
      }
    }
    stage('Build') {
      steps { 
        bat 'mvn test' 
      }
    }
  }
}
