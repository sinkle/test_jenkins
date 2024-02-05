pipeline {
    agent {
        label "linux"
    }
    stages {
        stage ('Init') {
            steps {
                sh 'hostname'
            }
        }
        stage ('Unit test') {
            steps {
                sh 'echo Unit testing'
            }
        }
    }
}
