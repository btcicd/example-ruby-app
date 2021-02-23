@Library('CICD_Sonarqube-NonEP-lib@mule') _

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
