pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Find latest release tag'
                sh '.\find_latest.sh'
                echo 'Build a docker image'
                sh '.\Dockerfile'
            }
        }
    }
}
