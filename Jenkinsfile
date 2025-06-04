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
        stage('Install dependencies & run tests') {
            steps {
                echo 'Installing dependencies'
                sh 'npm install'
            }
            steps {
                echo 'Running tests'
                sh 'npm test'
            }
        }
    }
}
