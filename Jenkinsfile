pipeline {
    agent any
    stages {
        steps('Clone Cluster Code') {
            sh "git clone https://github.com/martinoywa/test-project.git"
        }
        steps('Check folders') {
            ls -la
        }
    }
}