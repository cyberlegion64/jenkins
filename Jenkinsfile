pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'echo "build...."'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "test...."'
                sh 'echo "test....more more"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying...."'
                sh 'echo "Deploying more...."'
                sh 'echo "Deploying more and more...."'
            }
        }
    }
}
