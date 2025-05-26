pipeline {
    agent any
    stages {
        stage('Compile Java') {
            steps {
                sh 'javac hello.java'
            }
        }
        stage('Run Java') {
            steps {
                sh 'java HelloWorld'
            }
        }
    }
}
