@Library('Javalibrarary') _
pipeline{
    agent any
    stages{
        stage('SCM'){
            steps{
                git branch: 'main', url: 'https://github.com/akssharma1994/sharedlib.git'
            }
        }
        stage("Demo"){
            steps{
                welcome("Arun Sharma")
                welcome("Sharma")
                script{
                    calculator.add(4,8)
                    calculator.mul(4,8)
                }
            }
            
        }
        stage("another use"){
            steps{
                welcome("Sharma ji")
            }
        }
    }
}