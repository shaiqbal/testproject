node {
    stage 'Checkout'
        /* Checkout the code we are currently running against */
	    checkout scm

	        stage 'Build'
		    /* Build the Docker image with a Dockerfile, tagging it with the build number */
		        def app = docker.build "mabubackar/testproject:${env.BUILD_NUMBER}"
			}
