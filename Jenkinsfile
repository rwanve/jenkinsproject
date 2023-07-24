@Library('my-shared-library') _
pipeline {
    agent 

    stages {
        stage('Git checkout') {
            steps {
               gitcheckout{
                   branch "main"
                   url: "https://github.com/rwanve/jenkinsproject.git"
               }
            }
        }
    }
}
