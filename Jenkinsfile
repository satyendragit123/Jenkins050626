pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main',
                    credentialsId: 'githubcreds',
                    url: 'https://github.com/satyendragit123/Jenkins050626.git'
            }
        }

        stage('Hello') {
            steps {
                echo 'Jenkins Pipeline is working'
            }
        }
    }
}
