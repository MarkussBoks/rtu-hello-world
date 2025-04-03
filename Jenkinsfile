pipeline {
    agent any
    parameters{
        string(name: 'NAME',defaultValue: 'World',description: 'Personal name')
    }

    stages {
        stage('Hello') {
            steps {
                echo "Hello ${params.NAME}"
            }
        }
    }
}
