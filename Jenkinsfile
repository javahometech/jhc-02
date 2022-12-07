
pipeline{
  agent any
  
  environment{
    DEMO = "DEMO"
  }

  stages{
    stage("Load ENV"){
      steps{
        load 'env.groovy'
      }
    }
    stage("Load Demo"){
      steps{
        sh "printenv | grep DEMO"
      }
    }
    stage("Load Two"){
      steps{
        sh "printenv"
      }
    }
  }
}
