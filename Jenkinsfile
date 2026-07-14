pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building Version 2"
            }
        }

        stage('Test') {
            steps {
                echo "Running Tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying Application..."
            }
        }
    }

    post {
        always {
            echo "Pipeline Finished"
        }
    }
}
