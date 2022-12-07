
pipeline{
  agent any
  
  environment{
    DEMO = "DEMO"
  }

  stages{
    stage("Load Demo"){
      steps{
        load 'hari.groovy'
        sh "printenv"
      }
    }
  }
}
