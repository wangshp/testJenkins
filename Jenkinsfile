pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                bat 'set'
                echo helloworld > hello.txt
                more hello.txt
            }
        }
    }
}
