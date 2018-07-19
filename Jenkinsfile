pipeline {
  agent any
  stages {
    stage ("Build") {
      steps {
        echo 'Running Build Automation'
        sh './gradelew build --no-deamon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
