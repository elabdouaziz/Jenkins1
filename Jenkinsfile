pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                withEnv(["PATH=/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:$PATH"]) {
                    sh 'docker version'
                    sh 'docker build -t myimage .'
                }
            }
        }
    }
}
