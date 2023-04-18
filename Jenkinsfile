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
                bat 'copy /S "*" "D:\devops\htdocs\exp4" /Y'
            }
        }
        stage('Printing done') {
            steps {
                echo 'Done'
            }
        }
    }
}

  
