pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'python --version'
            }
        }
        stage('Test') {
            steps {
                sh 'pwd'
            }
        }
        stage('Deploy') {
            steps {
                sh 'sh test.sh'
            }
        }
    }
}
