node {
    checkout scm

    def customImage = docker.build("openjdk:${env.BUILD_ID}")
    /* def mvn = docker.build("maven:3-alpine:${env.}*/
    customImage.inside {
       echo $env.BUILD_ID
        
    }
   
}
