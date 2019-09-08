pipeline {

  agent any
  stages {
    stage('Build') {
     steps {
      echo "Testing Jenkinsfile"
     }
    }
     stage('PostBuild') {
      steps {
       echo ${date}
      }
    }
  }

}
