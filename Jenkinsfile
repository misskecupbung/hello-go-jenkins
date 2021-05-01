pipeline {

    agent any

    environment {
        GO111MODULE = 'on'
    }

    tools {
        go 'go-1.13'
    }

    stages {
        stage('Build') {
            steps {
                sh 'go build'
            }
        }
    }
}
