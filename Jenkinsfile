pipeline {

    agent { label 'aws-slave' } 

    parameters{
        agentParameter name:'agent-name'
    }

    stages {
        stage("Run index file"){
            steps {
                sh 'node index.js'
            }
        }
    }
}