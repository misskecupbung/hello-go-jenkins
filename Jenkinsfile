pipeline {

    agent any

    tools {
        go 'go-1.13'
    }
    
    environment {
        GO111MODULE = 'on'
    }

    stages {
        stage('Build') {
            steps {
                sh 'go build'
            }
        }
    }
}
