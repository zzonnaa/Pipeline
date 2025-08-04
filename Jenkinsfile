pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Compile'){
            steps{
                bat 'javac Hello.java'
            }
        }
        stage('Run'){
            steps{
                bat 'java Hello'
            }
        }
        
    }
}
