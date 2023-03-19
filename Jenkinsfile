pipeline {
    agent any
    
    tools {nodejs "node"}

    stages {
        stage('Git pull source code'){
            steps{
                git branch:'master',url: 'https://github.com/pkoriris/week6assigmnet.git'
            }
        }
        stage('compile source code'){
            steps{
                bat ''' cd C:\\Users\\Admin\\Documents\\gallery
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
