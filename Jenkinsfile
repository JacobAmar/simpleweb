pipeline {
    agent any
    stages {
        stage('Installing the helm chart :)') {
            steps{
              sh 'helm upgrade -i -n simple-web -f ${WORKSPACE}/values.yaml simple-web ${WORKSPACE}'
            }
        }
    }
}
