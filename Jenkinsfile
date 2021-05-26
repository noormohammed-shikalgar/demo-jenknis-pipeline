pipeline {
    
    agent { label params['agent-name'] } 

    parameters{
        agentParameter name:'agent-name'
    }

    stages {
        stage("Run index file"){
            steps {
                sh node index.js
            }
        }
    }
}