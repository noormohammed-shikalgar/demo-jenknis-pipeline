pipeline {

    agent { label 'aws-slave' } 

    stages {
        stage("Run index file"){
            steps {
                sh 'node index.js'
            }
        }
    }
}