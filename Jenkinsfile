pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'javac sub.java'
            }
        }
        stage('Run') {
            steps {
                bat 'java sub'
            }
        }
    }
}
