pipeline {

    // Version 1.0.0
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sh "git fetch origin"
                sh "git branch -av"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}