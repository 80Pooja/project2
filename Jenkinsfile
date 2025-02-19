pipeline {
    agent { label 'slave4' }
   stages {
        stage('example') {  
           when {
               branch 'dev1'
           }
             steps {
               echo "testing"
            }
        }
   }
}
