pipeline {

    agent any

    tools {
        go 'go-1.12'
    }
    
    environment {
        GO111MODULE = 'on'
        CGO_ENABLED = 0 
        GOPATH = "${JENKINS_HOME}/jobs/${JOB_NAME}/builds/${BUILD_ID}"
    }

    stages {
        stage('Build') {
            steps {
                sh 'go build'
            }
        }
    }
}
