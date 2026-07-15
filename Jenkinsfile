pipeline {
    agent any

    parameters {
        choice(
            name: 'ENV',
            choices: ['Dev', 'QA', 'Stage', 'Production'],
            description: 'Select Deployment Environment'
        )
    }

    stages {
        stage('Deploy') {
            steps {
                echo "Deploying to ${params.ENV}"
            }
        }
    }
}
