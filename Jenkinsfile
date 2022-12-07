load 'hari.groovy'
pipeline{
  agent any
  
  environment{
    DEMO = "DEMO"
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
