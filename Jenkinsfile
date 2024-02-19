pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                // Add build commands here
            }
        }
        stage('Test') {
            steps {
                echo 'Running tests...'
                // Add test commands here
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the application...'
                // Add deployment commands here
            }
        }
    }

    post {
        success {
            echo 'Pipeline succeeded! Yay!'
            // Add any success post-processing here
        }
        failure {
            echo 'Pipeline failed! Oh no!'
            // Add any failure post-processing here
        }
    }
}
