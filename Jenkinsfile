pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building branch: ${env.BRANCH_NAME}"
                // Add your build commands here, e.g.:
                bat 'echo Build step for Windows'
                // or sh 'echo Build step for Linux'
            }
        }
        stage('Test') {
            steps {
                echo "Testing branch: ${env.BRANCH_NAME}"
                // Add test commands here
            }
        }
    }
}
