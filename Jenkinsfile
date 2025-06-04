pipeline {
    agent any
    tools {
        nodejs '22.16.0'
    }

    stages {
        // stage('Fetch code') {
        //     steps {
        //         git branch: 'master', credentials
        //     }
        // }
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh 'npm -v'
                sh 'node -v'
            }
        }
    }
}
