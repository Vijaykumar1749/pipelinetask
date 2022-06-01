pipeline {
    agent Linux

    stages {
        stage('Build') {
            steps {
                sh 'javac Hello.java'
            }
        }
        stage('Run') {
            steps {
                sh 'java Hello'
            }
        }
    }
}
