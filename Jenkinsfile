pipeline {
    agent any

    parameters {
        booleanParam(
            name: 'RUN_TESTS',
            defaultValue: true,
            description: 'Run Test Stage?'
        )
    }

    stages {

        stage('Build') {
            steps {
                echo "Building..."
            }
        }

        stage('Test') {
            when {
                expression {
                    return params.RUN_TESTS
                }
            }

            steps {
                echo "Running Tests..."
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying..."
            }
        }
    }
}
