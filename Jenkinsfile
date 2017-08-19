pipeline {
    agent any
    stages {
        stage("Permission")
        steps {
             // withDockerRegistry([credentialsId: 'b6ef8f34-268d-4a12-a02f-c0eb8bf002ec', url: "https://hub.docker.com/"]) {

               // script {
        // we give the image the same version as the .war package
             // def image = docker.build("prakashul/knowledgemeet:latest",'.')
             // image.push()

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
                               // }
              }
            }
}
