pipeline {
    agent any

    environment {
        APP_PORT = '9090'
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building the application...'
                sh "mvn clean package"
            }
        }

        stage('Unit Tests') {
            steps {
                echo 'Running unit tests...'
                sh "mvn test"
            }
        }
    }
}
