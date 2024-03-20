pipeline {
    agent any
    options {
        timeout(time:1, unit: 'SECONDS')
}
    stages {
        stage('Example') {
            steps {
                sh 'touch file.txt'
            }
        }
    }
}
