pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'mvn'
            }
        }
        stage('Test') {
            steps {
                sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
