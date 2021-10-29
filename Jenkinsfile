node('docker') {
    stage('test') {
        checkout scm
        waitK8sResources('deploy.yaml')
    }
}
