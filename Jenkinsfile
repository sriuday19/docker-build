pipeline{
    agent any
    
    stages {
        stage('build image') {
            script {
                docker_image = docker.build("sriuday19/vprofileapp:${env.BUILD_NUMBER}", "./Dockerfiles/app/")
            }
        }
    }
}