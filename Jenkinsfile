pipeline {
   agent any

   stages {
       stage('node_exporter') {
           steps {
               ssh -i iocmigration.pem ubuntu@$IP_ADDRESS
               sudo ls -al
           }
       }
   }
}