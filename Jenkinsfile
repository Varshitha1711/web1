pipeline {
    agent any  

    stages {
        stage('Get Code') {  
            steps {
                git url: 'https://github.com/Varshitha1711/web1.git', branch: 'main' 
            }
        }
        stage('Build') {  
            steps {
                echo 'Trying to build the project...'
                sh 'ls'  // List files (Windows equivalent of 'ls')
            }
        }
        stage('Test') {  
            steps {
                echo 'Running tests...'
            }
        }
         stage('Deploy') {  
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}
