pipeline {
    agent any
    stages {
        stage('Checking python version') {
            steps {
                bat 'python -v'
            }
        }
        stage('Cloning repository') {
            steps {
                bat 'copy "C:\Users\HP\.jenkins\workspace\abhishek\*" "E:\devops\htdocs\exp4\" /Y /S'
            }
        }
        stage('Printing done') {
            steps {
                echo 'Done'
            }
        }
    }
}

  
