pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
                echo "Building the code"
            }
        }
        stage('Test') {
            steps {
                echo "Testing the code"
            }
        }        
    }
}
