pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'build'
            }
        }
        stage('Change') {
            steps {
                snDevOpsChange changeCreationTimeOut: 3600, changeRequestDetails: '{ "attributes": { model: \'devops\'}', changeStepTimeOut: 18000, pollingInterval: 60
            }
        }
    }
}
