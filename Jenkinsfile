node('docker') {
    stage('test') {
        checkout scm
        def files = [
            ~'aaa.*bb',
            ~'bbb.*aaa',
        ]
        println debug(files)
    }
}
