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
                bat 'xcopy /S "*" " E:/devops/htdocs/exp4" /Y'
            }
        }
        stage('Printing done') {
            steps {
                echo 'Done'
            }
        }
    }
}

  
