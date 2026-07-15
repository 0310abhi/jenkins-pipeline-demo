parameters {
    string(name: 'NAME', defaultValue: 'Abhinav')
}

environment {
    NAME = "Rahul"
}

stages {
    stage('Demo') {
        steps {
            echo "${params.NAME}"
            sh 'echo $NAME'
        }
    }
}
