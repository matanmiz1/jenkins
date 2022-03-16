pipeline {
  
  agent any
  
  parameters {
    	choice(choices: ['us', 'eu', 'jp', 'au', 'ca', 'uk'], description: 'AWS region', name: 'region', defaultValue: 'uk') 
  }
  stages {
    
    stage ("build") {
      
      steps {
        sh 'echo "Building"'
      }
    }
    
    stage ("test") {
      
      steps {
        sh 'echo "Testing"'
      }
    }
    
    stage ("deploy") {
      
      steps {
        sh 'echo "Deploying"'
      }
    }
  }
}
