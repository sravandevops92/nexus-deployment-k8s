pipeline {
  agent any 
tools {
  docker 'docker'
}
stages {
  stage ('nexus deployment') {
    steps {
       script {
         //sh "kubectl apply -f k8s"
         sh "docker --version"
       }
    }
  }
 }
}
