pipeline {
    agent any

    stages {
        stage('NewButton') {
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
