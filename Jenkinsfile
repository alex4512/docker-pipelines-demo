node {
    checkout scm

    def customImage = docker.build("openjdk:${env.BUILD_ID}")
    
    customImage.inside {
       echo $env.BUILD_ID
        
    }
   
}
