node('java-docker-slave') {
    stage ('Build Image') {
        sh 'make build'
    }
    stage ('Push Image') {
        sh 'make push'
    }
    stage ('Deploy to Container') {
        sh 'make deploy'
    }
}
