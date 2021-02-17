@Library('CICD_Sonarqube-NonEP-lib') _

pipeline {
    agent any
    tools { jdk 'OpenJDK 11' }
    stages {
        stage('ruby') {
            steps {
                sonarScan()
            }
        }
   
    }
}
