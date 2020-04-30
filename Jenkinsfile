node {
    checkout scm

    def customImage = docker.build("node-app:${env.BUILD_ID}")

    customImage.inside {
        sh 'node --version'
    }
}
