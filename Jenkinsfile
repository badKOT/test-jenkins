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
        sh 'echo $(cat file1.txt file2.txt) | grep "Hello world"'
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
        
        
