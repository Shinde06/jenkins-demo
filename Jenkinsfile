echo 'pipeline {
    agent any

    stages {
        stage("Clone Repo") {
            steps {
                echo "Cloning repository..."
                // Already done by Jenkins if using SCM
            }
        }

        stage("Build") {
            steps {
                echo "Simulating build..."
                sh "ls -l"
            }
        }

        stage("Deploy") {
            steps {
                echo "Deploy step (placeholder)..."
                // Add deployment script here
            }
        }
    }
}' > Jenkinsfile

