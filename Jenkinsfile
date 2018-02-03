node {
    checkout scm
    def comment = pullRequest.comment('This PR is highly illogical..')
    def customImage = docker.build("geezyx/docker-ruby-nodejs:${env.BUILD_ID}")
}
