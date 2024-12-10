pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'build'
            }
        }
        stage('Test'){
            steps{
                echo 'test'
            }
        }
        stage('Security'){
            steps{
                echo 'security'
            }
        }
        stage('Change') {
            steps {
                snDevOpsChange()
            }
        }
    }
}
