pipeline {
  agent any
  
  tools {
    gradle 'MyGradle'
  }
  
  stages {
    stage ('What happens to gradle?') {
      steps {
        echo 'Check gradle...'
        echo '$PATH'
        echo 'uname -a'
        echo 'top'
      }
    }    
  }  
}
