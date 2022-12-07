pipeline{
  agent any
  
  environment{
    load 'hari.groovy'
  }

  stages{
    stage("Load Demo"){
      steps{
        echo "Hello"
        sh "printenv"
      }
    }
  }
}
