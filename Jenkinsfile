node('docker') {
    stage('test') {
        def scmInfo = checkout scm
        getGitBranchFromScm(scmInfo)
    }
}
