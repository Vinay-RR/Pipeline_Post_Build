pipeline {
  agent {
  label 'C_Test'
}	
  stages {
    stage ('BUILD') {
      steps {
       git branch: 'main', url: 'https://github.com/Vinay-RR/Test_C_Project.git'
        sh 'sleep 5'
      }  
    } 
    post {
  always {
    agent {
      label '
    stage ('BUILD') {
      steps {
    git branch: 'main', url: 'https://github.com/Vinay-RR/Test-java-project.git'
        sh 'sleep 5'
      }
    }
  }
}
     }
  }
