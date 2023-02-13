pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'python welcome'
                bat 'python click.py'
            }
        }
    }
}
