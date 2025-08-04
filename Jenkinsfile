pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Building'
                bat 'javac Hello.java'
                bat 'java Hello'
            }
        }
    }
}
