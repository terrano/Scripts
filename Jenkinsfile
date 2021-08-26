pipeline {
  agent any
  
  tools {
    gradle 'MyGradle'
  }
  
  stages {
    stage ('What happens to gradle?') {
      steps {
        echo 'Check gradle...'
        sh '$PATH'
        sh 'uname -a'
        sh 'top'
      }
    }    
  }  
}
