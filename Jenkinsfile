/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'winamd64/golang' } }
    stages {
        stage('build') {
            steps {
                sh 'go version'
            }
        }
    }
}
