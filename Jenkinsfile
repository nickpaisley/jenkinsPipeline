pipeline{
  agent none
  stages{
    stage('QA'){
      agent{
        label 'vm115'
      }
      steps{
        testcompletetest credentialsId: '3d987b1f-e614-4552-97c1-48fc7e9a4f82', 
        executorType: 'TE',
        suite: 'C:\\dev\\repos\\np_jenkinsPipeline\\jenkinsPipeline\\Jenkins.pjs', 
        useTCService: true
      }
    }
  }
}