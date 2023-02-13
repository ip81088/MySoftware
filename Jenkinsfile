pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'python welcome'
                bat 'python click.py'
            }
        }
        stage('Click') {    
            steps {
            bat 'python click.py'
            }    
        }
    }
}
