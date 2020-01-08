pipeline {
    agent { docker { image 'python:3.7.6' } }
    stages {
        stage('build') {
            steps {
                zsh 'python --version'
            }
        }
    }
}
