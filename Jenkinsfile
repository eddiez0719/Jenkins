pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Install JQ'
                sh 'sudo apt-get install jq'
                echo 'Find latest release tag and build a docker image'
                sh './find_latest.sh'
            }
        }
    }
}
