pipeline {
 agent {
    node { label 'workstation' }
 }

   stages {
        stage ('build') {
          steps {
            sh 'echo build'
            sh 'npm install'
          }
        }
   }
   stages {
        stage ('Unit test') {
          steps {
            sh 'echo test passed'
          }
        }
   }
   stages {
        stage ('Code Coverage') {
          steps {
            sh 'echo Code Coverage'
          }
        }
   }
   stages {
        stage ('security checks') {
          steps {
            sh 'echo security check passed'
          }
        }
   }
   stages {
        stage ('Publish an artifactory') {
          steps {
            sh 'echo published an artifactory'
          }
        }
   }


}