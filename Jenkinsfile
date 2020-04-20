node {
    checkout scm

    def customImage = docker.build("openjdk:${env.BUILD_ID}")

    customImage.inside {
        sh 'java -version'
    }
}
