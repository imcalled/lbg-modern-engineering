pipeline{
  agent any
  stages{
    stage('Make Directory'){
      steps{
        sh "mkdir ~/jenkins-pipeline-test"
      }
    }
    stage('Make Files'){
      steps{
        sh "touch ~/jenkins-pipeline-test/file"
      }
    }
  }
}
