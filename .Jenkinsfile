pipeline{
  agent none
  stages{
    stage('QA'){
      agent{
        label ''
      }
      steps{
        testcompletetest credentialsId: '', 
        executorType: 'TE',
        suite: 'C:\\Users\\sb\\.jenkins\\workspace\\TC_Pipeline_GH_NP_Test1\\Jenkins.pjs', 
        useTCService: true
      }
    }
  }
}