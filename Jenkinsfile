
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Starting Jenkins Build'
                sh 'python3 --version'
                sh 'python3 hello.py'
            }
        }

        stage('Success') {
            steps {
                echo 'Build completed successfully'
            }
        }
    }
}
