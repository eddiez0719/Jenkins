pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Find latest release tag and build a docker image'
                sh './find_latest.sh'
            }
        }
    }
}
