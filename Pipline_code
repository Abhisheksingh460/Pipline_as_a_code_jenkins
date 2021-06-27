pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo "my first step is build"
                sleep 2
            }
        }
        
        stage('Test') {
            steps {
                echo "test"
                sleep 4
            }
        }
        
        stage('Deploy') {
            steps {
                echo "deploy"
                sleep 6
            }
        }
    }
}
