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
        sh 'cat start.txt end.txt | grep -q "Hello world"'
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
        
        
