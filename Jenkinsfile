pipeline {
  agent any 
  stages {
    stage('Build'){
      steps{
        echo 'Running the build automation'
        sh './gradlew build --no-daemon'
        arhicveArtifacts artifacts: 'dist/trainSchedule.zip'
    }
  }
      
}
