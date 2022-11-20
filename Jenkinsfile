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
  }
    post {
  always {
    echo "I will always execute this"
        sh 'sleep 5'
      }
    }
  }
