@Library('my-shared-library@main') _

def pipelineParams = [
    dockerHubUsername: 'suraj009',
    dockerImageName: 'my-test-java',
    tag: 'v1',
    credentialsId: 'docker-hub-credentials'
]
mavenJarPipeline.call(pipelineParams)

