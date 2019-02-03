pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                sh 'java -version'
                sh 'python --version'
                writeFile file: 'hello.ruby', text: 'Hello world from Ruby' 
            }
        }
    }
}
