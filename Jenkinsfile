pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build stage'
                // your build steps here
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage'
                sh 'test -f build/index.html'
                sh 'npm test'
            }
        }

    }
}
