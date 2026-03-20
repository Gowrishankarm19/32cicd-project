pipeline {
    agent any

    environment {
        DOCKER_CREDS    = credentials('dockerhub-creds')
        KUBECONFIG_DATA = credentials('k3s-config')
        IMAGE_NAME      = "Gowrishankar19/project1"
    }

    stages {

        stage('Checkout Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/Gowrishankar19/32cicd-project'
            }
        }

    } 
}

  
