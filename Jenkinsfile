pipeline {
  
  agent any
  stages {
    
    stage ('Building stage') {
      steps {
        echo 'Building the application...'
      }
    }

    stage ('Testing stage') {
      steps {
        echo 'Testing the application...'
        sh 'echo $(cat start.txt end.txt) | grep "Hello world"'
        echo 'Application tested!'
      }
    }

    stage ('Final stage') {
      steps {
        echo 'Wrapping up...'
      }
    }
  }
}
        
        
