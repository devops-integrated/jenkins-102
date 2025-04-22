pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/devops-integrated/jenkins-102.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                // your build commands here, like mvn install or npm run build
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying to OpenShift (future step)'
            }
        }
    }
}

