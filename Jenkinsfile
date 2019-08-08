pipeline {
  agent any
  stage {
    stage ('Build') {
      stage {
      echo "Running build Automation"
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts : 'dist/trainSchedule.zip'
      }
    
    }
  
  }

}
