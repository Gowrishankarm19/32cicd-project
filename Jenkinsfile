pipeline {
    agent any

    environment {
        DOCKER_CREDS    = credentials('dockerhub-creds')
        KUBECONFIG_DATA = credentials('k3s-config')
        IMAGE_NAME      = "gowrishankar19/project1"
    }

    stages {

        stage('Checkout Code') {
            steps {
                git branch: 'main',
                    url: 'https://github.com/gowrishankar19/31cicd-project'
            }
        }

    } 
}

  
