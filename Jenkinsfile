pipeline {
    agent any
    stages{
        stage('Build'){
            steps {
                bat 'mvn clean package'
                //bat "docker build . -t dockerpipe:${env.BUILD_ID}"
            }
            

        }
    }
}
