
node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'Dockerhubcreds') {

        def customImage = docker.build("mastanvali123/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
