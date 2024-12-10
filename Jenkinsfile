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
        stage('Change') {
            steps {
                snDevOpsChange()
            }
        }
    }
}
