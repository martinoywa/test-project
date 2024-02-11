pipeline {
    agent any
    stages {
        stage('Clone Cluster Code') {
            steps {
                sh "cd ."
                sh "git clone https://github.com/martinoywa/test-cluster.git"
            }
        }

        stage('Check folders') {
            steps {
                dir(".") {
                    sh "ls -la"
                }
            }
        }
    }
}