pipeline {
    agent any

    stages {
        stage('Git checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/rwanve/jenkinsproject.git'
            }
        }
    }
}
