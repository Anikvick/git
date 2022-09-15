pipeline{
  agent{
    label{
      label "built-in"
      customWorkspace "/mnt/job/jenkinsfile"
  }
 }
 stages{
  stage("first"){
    steps{
      sh "mkdir folder1"
      sh "touch f1 f2"
    }
  }
 } 
}
