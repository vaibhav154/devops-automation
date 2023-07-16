pipeline {
    agent any
    
    stages {
        stage('SSH to EC2 Instance') {
            steps {
                echo "Hello"
                // Define the SSH credentials
                withCredentials([sshUserPrivateKey(credentialsId: 'SSH_CREDENTIALS_ID', keyFileVariable: 'SSH_KEY')]) {
                    // // SSH connection details
                    // def remoteHost = 'YOUR_EC2_INSTANCE_PUBLIC_DNS'
                    // def remoteUser = 'YOUR_EC2_INSTANCE_USERNAME'
                    
                    // // SSH command to execute on the EC2 instance
                    // def sshCommand = "ssh -o StrictHostKeyChecking=no -i $SSH_KEY ${remoteUser}@${remoteHost} ls -la"
                    
                    // // Execute SSH command
                    // def sshResult = sh(returnStdout: true, script: sshCommand)
                    
                    // // Print the output
                    // echo "SSH Output:\n${sshResult}"
                }
            }
        }
    }
}