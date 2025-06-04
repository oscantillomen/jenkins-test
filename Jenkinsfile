pipeline {
    agent any
    tools {
        nodejs '22.16.0'
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'npm -v'
                sh 'node -v'
            }
        }
        stage('Install dependencies') {
            steps {
                echo 'Installing dependencies'
                sh 'npm install'
            }
        }
        stage('Run tests') {
            steps {
                echo 'Running tests'
                sh 'npm run test'
            }
        }
        stage('Run Build') {
            steps {
                echo 'Building'
                sh 'npm run build'
            }
        }
    }
}
