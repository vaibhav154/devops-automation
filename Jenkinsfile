pipeline {
    agent any
    stages {
        stage('Hello_world') {
            steps {
                sshagent(['iocmigration.pem']) {
                    sh 'ssh ubuntu@52.76.226.63'
                    sh 'ls -al'
                }
            }
        }
    }
}