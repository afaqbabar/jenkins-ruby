pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                #writeFile file: 'hello.ruby', text: 'Hello world from Ruby'
                echo "puts 'Hello World from Ruby using puts'" > helloworld.rb 
            }
        }
    }
}
