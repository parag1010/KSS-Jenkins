pipeline {
    agent any
    stages {
        stage("Permission")
        steps {
        try {
            timeout(time: 20, unit: 'SECONDS') { 
            input 'Do you want to proceed to the Deployment?'
        }
  }
        catch(err) {
                err.printStackTrace()
                                                }
                sh 'echo Proceeding To Deployment'
               }
              }
            }
}
