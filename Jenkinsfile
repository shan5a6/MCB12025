def myadd(a,b) {
  sum = a+b
  println "sum of ${a} & ${b} is ${sum}"
}
pipeline {
  /*agent server1/docker/kubernetes/any*/
  agent any 
  stages {
    stage('git checkout') {
      steps {
        script {
            myadd(10,20)
            myadd(100,200)
            myadd(300,400)
        }
      }
    }
  } 
}
