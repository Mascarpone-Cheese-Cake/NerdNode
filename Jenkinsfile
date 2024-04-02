pipeline {
    agent any
    stages {

        stage('github-clone') {
            steps {
                git branch: 'BE', credentialsId: 'github_token', url: '{REPOSITORY URL}'
                echo 'Clone Repository...'
            }
        }


        stage('build') {
            steps {
                echo 'building the application...'
            }
        }
        stage('test') {
            steps {
                echo 'testing the application...'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploying the application...'
            }
        }
    }
}
