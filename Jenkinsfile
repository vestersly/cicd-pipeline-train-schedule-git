pipeline {
  agent any
  stages{
  stage {"Build"} {
    steps {
      echo"Running build automation"
      sh "./gralew build --no-daemon"
      archiveArtifacts artifacts: "dist/trainSchudle.zip"
    }
  }
  }
}
