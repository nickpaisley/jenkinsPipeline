pipeline{
  agent none
  stages{
    stage('QA'){
      agent{
        label 'VM107'
      }
      steps{
        testcompletetest credentialsId: '3d987b1f-e614-4552-97c1-48fc7e9a4f82', 
        executorType: 'TE',
        suite: 'C:\\Users\\sb\\.jenkins\\workspace\\TC_Pipeline_NP\\Jenkins.pjs', 
        useTCService: true
      }
    }
  }
}