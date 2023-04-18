pipeline {
    agent any
    stages {
        stage('Checking python version') {
            steps {
                bat 'python --version'
            }
        }
        stage('Cloning repository') {
            steps {
                bat 'git clone <repository URL> C:/Xamp/htdocs/exp4'
            }
        }
        stage('Printing done') {
            steps {
                echo 'Done'
            }
        }
    }
}

  
