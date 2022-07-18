node {

    checkout scm

    docker.('https://hub.docker.com/', 'dockerHub') {

        def customImage = docker.build("mastanvali123/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
