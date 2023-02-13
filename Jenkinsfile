pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'python welcome'
            }
        }
        stage('Click') {    
            steps {
            bat 'python click.py'
            }    
        }
    }
}
