pipeline {
  
  agent any
  
  parameters {
    	string(defaultValue: "default", description: 'time zone, default depends on region ot previous group vars', name: 'tz')
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
