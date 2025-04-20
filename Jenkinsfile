pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/23B81A6755CSD/SEDEVOPS.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building the project...'
                // Run build commands like javac, mvn install, etc.
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Run test commands like pytest, mvn test, etc.
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Deployment script or commands
            }
        }
    }
}
