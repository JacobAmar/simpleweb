pipeline {
    agent { label 'jenkins-helm' }
    stages {
        stage('Installing the helm chart :)') {
            steps{
              sh 'helm upgrade -n simple-web -f ${WORKSPACE}/values.yaml simple-web ${WORKSPACE}'
            }
        }
    }
}