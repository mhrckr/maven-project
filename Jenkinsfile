pipeline {
    agent any
    stages{
        stage('Build'){
            steps {
                bat 'mvn clean package'
                bat "docker build . -t Docker-Pipeline:${env.BUILD_ID}"
            }
            

        }
    }
}
