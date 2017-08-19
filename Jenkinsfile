pipeline {
   agent any
    stages {
       stage('Permissions') {
       steps {
               script {
           try {
              timeout(time: 20, unit: 'SECONDS') {
              input 'Do you want to proceed to the Deployment?'
      }
              }
      catch(err) {
              err.printStackTrace()
                                            }
              sh 'echo Proceeding To Deployment'
             }}

   }

       }
}
