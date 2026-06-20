pipeline {
    agent any

    stages {

        stage('build') {
            steps {
                echo 'build started'
            }
        }

        stage('run python') {
            steps {
                sh 'python3 hello.py'
            }
        }

    }
}
