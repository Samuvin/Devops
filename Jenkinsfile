pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                echo "Cloning repository..."
            }
        }

        stage('Build') {
            steps {
                echo "Building the project..."
                // Put build commands here, like: sh 'npm install' or sh './gradlew build'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                // Put test commands here, like: sh 'npm test'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploying application..."
                // Deployment steps here
            }
        }
    }
}
