pipeline {
    agent any 
    stages {
        stage('Checkout') {
            steps {
                cleanWs()
                sh 'git clone https://github.com/jabedhasan21/java-hello-world-with-maven'
                sh 'java -version'
            }
        }
        stage('Build') {
            steps {
                sh 'cd java-hello-world-with-maven; mvn install '
            }
        }
    }    
}
