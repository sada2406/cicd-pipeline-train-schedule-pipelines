pipeline {
  agent any
  stages {
    stage ('Build') {
      stage {
      echo "Running build Automation"
      sh './gradlew build --no-daemon'
      archiveArtifacts artifacts : 'dist/trainSchedule.zip'
      }
    
    }
  
  }

}
