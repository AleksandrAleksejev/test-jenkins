pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage("Create a file and read it"){
            steps{
                sh 'echo "Hello from the file:)"> hello.txt'
                sh 'cat hello.txt'
            }
        }
    }
}
