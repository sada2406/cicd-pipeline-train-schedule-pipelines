pipeline {
  agent any
  stage {
    stage (Build) {
      stage {
      echo "Running build Automation"
      ./gradlew build --no-daemon
      archiveArtifacts artifacts : 'dist/trainSchedule.zip'
      }
    
    }
  
  }

}
