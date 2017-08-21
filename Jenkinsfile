pipeline {
  agent any
  stages {
    stage('Build Dependances') {
      steps {
        parallel(
          "Build Dependances": {
            echo 'test'
            
          },
          "DoMore": {
            echo 'aaa'
            
          }
        )
      }
    }
    stage('Build LabVIEW') {
      steps {
        echo 'Building LabVIEW1'
        echo 'Build LabVIEW2'
      }
    }
  }
}