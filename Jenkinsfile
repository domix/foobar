pipeline {
    agent any
    stages {
        stage('Example stage 1') {
            steps {
              withCredentials([[$class: 'UsernamePasswordMultiBinding', credentialsId: 'docker_registry_domix', usernameVariable: 'USERNAME', passwordVariable: 'PASSWORD']]) {
                sh './run.sh'
              }
            }
        }
    }
}