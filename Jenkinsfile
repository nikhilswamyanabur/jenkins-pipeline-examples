// Jenkinsfile
// ----------------------------------------------------------------------
// This is as simple as it gets with declarative pipeline
// ----------------------------------------------------------------------
pipeline {
   agent any
   environment{
   /home/ec2-user/apache-maven-3.8.6
   }
    stages {
      stage('Say Hello') {
         steps {
            echo 'Hello World!'
         }
      }
       stage(build) {
         steps {
            sh "mvn test"
         }
       }
   }
}
