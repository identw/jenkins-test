node('docker') {
    stage('test') {
        checkout scm
        waitK8sResources(k8sYamlFile: 'deploy.yaml', kinds: ['Deployment'], condition: 'Available')
    }
}
