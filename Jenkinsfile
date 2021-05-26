pipeline {
    agent "aws-slave"

    stages {
        stage("Run index file"){
            steps {
                sh node index.js
            }
        }
    }
}