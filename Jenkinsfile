pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Build Complete."'
                // sh 'echo "Triggering from github."'
                // sh 'echo "Triggering from Jenkins SCM."'
                sh 'echo "Triggering from Build Trigger Scheduled."'
            }
        }
    }
}