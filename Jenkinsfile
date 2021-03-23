@Library('CICD_Sonarqube-NonEP-lib') _

pipeline {
    agent any
    stages {
        stage('ruby') {
            steps {
                sonarScan("-Dsonar.sources=GettingStarted,YourApp")
            }
        }
   
    }
}
