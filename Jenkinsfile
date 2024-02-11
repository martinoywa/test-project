pipeline {
    agent any
    stages {
        stage('Clone Cluster Code') {
            steps {
                sh "git clone https://github.com/martinoywa/test-project.git"
            }
        }

        stage('Check folders') {
            steps {
                sh "ls -la"
            }
        }
    }
}