
pipeline{
  agent any
  
  environment{
    SINGLE_KEY=credentials('singlekey')
  }

  stages{
    stage("Load ENV"){
      steps{
        load 'env.groovy'
      }
    }
    stage("Load Demo"){
      steps{
        sh "printenv"
      }
    }
    stage("Load Two"){
      steps{
        sh "printenv"
      }
    }
  }
}
