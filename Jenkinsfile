pipeline{
 agent any
 stages{
   stage("deploy to prod"){
    when{
    branch 'master'
    }
    steps{
      echo "deploy in to production environment"
    }
   }
  stage("deploy to uat"){
    when{
    branch 'Release'
    }
    steps{
      echo "deploy in to uat environment"
    }
   }
  stage("deploy to dev"){
    when{
    branch 'develop'
    }
    steps{
      echo "deploy in to dev environment"
    }
   }
 }
}
