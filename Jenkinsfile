pipeline {
    agent any
    stages {
        stage('Example stage 1') {
            steps {
                withCredentials(bindings: [credential(credentialsId: 'docker_registry_domix',
                                                       
                                                       passwordVariable: 'PASSWORD')]) {
                  // 
                }
            }
        }
        stage('Example stage 2') {
            steps {
                // 
            }
        }
    }
}