pipeline {
    agent any

    stages {

        stage('Pull') {
            steps {
                git branch: 'main',
                url: 'https://github.com/SanikayYadav-123/python-jenkins-project.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Python Application...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Python Application...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying Python Application...'
            }
        }
    }
}