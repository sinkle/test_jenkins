pipeline {
    agent {
        label "linux"
    }
    stages {
        stage('Clone github repo'){
            steps {
                git url: 'https://github.com/sinkle/test_jenkins.git', branch: 'master'
            }
        }

        stage('Setup') {
            steps {
                sh 'pwd'
                sh 'pip install -r backend/src/requirements.txt'
            }
        }
    }
}
