pipeline {
    agent any
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python3 --version'
                sh pwd
                sh cat pipeline.py
                sh 'python3 pipeline.py'
            }
        }
    }
}
