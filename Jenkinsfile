pipeline {
    agent any
    stages {
        stage('Installing the helm chart :)') {
            steps{
              sh 'helm upgrade -n simple-web -f ./values.yaml simple-web .'
            }
        }
    }
}