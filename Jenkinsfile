pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                echo 'mvn -version' 
            }
        }
		stage('Test') { 
            steps {
                echo 'mvn test' 
            }
            post {
                always {
                  echo 'hello'
                }
            }
        }
    }
}