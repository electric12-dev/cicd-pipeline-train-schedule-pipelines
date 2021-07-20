pipeline {
  agent any
  stages {
    stage("build"){
      steps{
        echo "Running"
        sh './gradle build --no-daemon'
        archiveArtifacts artifacts 'dist/trainSuccess.zip'
      }
    }
  }
}
