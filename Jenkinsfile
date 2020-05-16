pipeline {
  agent any
  stages {
     stage("Test") {
     when { tag "v1.*" }
       steps {
          sh "echo PRODUCTION" 

       }
     }

  }
}
