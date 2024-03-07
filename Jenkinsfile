//Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any 
    stages {
        stage('Stage 2') {
            steps {
                git credentialsId: 'jenkinscred', url: 'https://github.com/s-mitta/personal.git'
            }
        }
    }
}
