pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                sleep 2
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                sleep 2
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sleep 2
            }
        }
        stage('Run first project') {
            steps {
                build 'ProjectTests1'
            }
        }
        stage('Run second project') {
            steps {
                build 'ProjectTests2'
            }
        }
    }
}