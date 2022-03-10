pipeline {
  agent {label "linux"}
  options {
    buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '5', daysToKeepStr: '', numToKeepStr: '5')
    disableConcurrentBuild()
  }
  stages {
    stage('Hello') {
      steps {
        echo "hello"
      }
    }
  }
} 		
