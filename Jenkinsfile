pipeline {
    agent any

    stages {
        stage('Git pull source code'){
            steps{
                git branch:'master',url: 'https://github.com/pkoriris/week6assigmnet.git'
            }
        }
        stage('compile source code'){
            steps{
                bat ''' cd C:\Windows\System32\cmd.exe
                npm install '''
            }
            
        }
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
