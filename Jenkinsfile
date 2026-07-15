pipeline {
    agent any

    environment {
        COMPANY = "OpenAI"
    }

    stages {

        stage('Build') {
            environment {
                VERSION = "1.0"
            }

            steps {
                echo "Company: ${COMPANY}"
                echo "Version: ${VERSION}"
            }
        }

        stage('Deploy') {
            steps {
                echo "Company: ${COMPANY}"
                echo "Version: ${VERSION}"
            }
        }
    }
}
