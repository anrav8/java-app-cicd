pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git clone https://github.com/jabedhasan21/java-hello-world-with-maven
                cd java-hello-world-with-maven
            }
        }
        stage('Build') {
            steps {
                mvn install
            }
        }
    }
}
