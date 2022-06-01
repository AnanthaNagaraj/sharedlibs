@Library('javahome-demo') _

pipeline{
    agent any
    stages{
        stage('Demo'){
            steps 
            {
                echo 'DEVELOP'
                welcome("Test Automation")
                script{
                calculator.add(4,5)    
                }
                
                
            }
        }
        
        stage('QA'){
            steps 
            {
                echo 'QA'
                welcome("Test Automation")
                
            }
        }
    }
}

