pipeline {
  /*agent server1/docker/kubernetes/any*/
  agent any 
  stages {
    stage('git checkout') {
      steps {
        script {
          a=10
          b=20
          if (a>b) {
            println "a:${a} is big"
          }
          else {
            println "b:${b} is big"
          }
        }
      }
    }
  } 
}
