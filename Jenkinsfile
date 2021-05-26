pipeline {

    agent { label 'aws-slave' } 

    tools { nodejs 'Nodejs - 14.17.0' }

    stages {
        stage("Run index file"){
            steps {
                sh 'node index.js'
            }
        }
    }
}