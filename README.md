# jekins

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo " hello wolrd"
            }
        }
        stage('Test') {
            steps {
                echo " hello wolrd test"
            }
        }
        stage('Deploy') {
            steps {
                echo "hello wolrd deployed"
            }
        }
    }
}
