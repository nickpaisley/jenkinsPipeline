pipeline{
  agent none
  stages{
    stage('QA'){
      agent{
        label 'VM107'
      }
      steps{
        testcompletetest credentialsId: '4cfb4bac-9a56-425c-9a34-a77933df681a', 
        executorType: 'TE',
        suite: 'C:\\Users\\sb\\.jenkins\\workspace\\TC_Pipeline_GH_NP_Test1\\Jenkins.pjs', 
        useTCService: true
      }
    }
  }
}