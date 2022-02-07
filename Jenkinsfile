node('docker') {
    stage('test') {
        checkout scm
        sh 'env | grep GIT_ || true'
        
        println "###########################"

        def scmInfo = checkout scm
        println scmInfo
    }
}
