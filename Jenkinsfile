pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'python welcome.py'
            }
        }
        stage('Click') {    
            steps {
            bat 'python click.py'
            }    
        }
    }
}
