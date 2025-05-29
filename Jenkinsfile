pipeline {
  /*agent server1/docker/kubernetes/any*/
  agent any 
  parameters {
    choice choices: ['dev', 'prod'], description: 'Select environment', name: 'ENV'
  }
  environment {
  JAVA_PATH = "/home/ec2-user/java/bin"
  }

  stages {
    stage('git checkout') {
      steps {
        script {
          var1=20
          println "my var1 value is ${var1}"
          println "my env value is ${params.ENV}"
          println "my JAVA_PATH is ${env.JAVA_PATH}"
        }
      }
    }
  } 
}
