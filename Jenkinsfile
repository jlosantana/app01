pipeline {
    agent { docker 'maven:3.3.3' }
    stages {
        stage('Checkout') {
            deleteDir()
            checkout scm
        }
    }
}
