pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git 'https://github.com/Shinde06/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build Step (placeholder)'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying index.html to Apache...'
                sh 'cp index.html /var/www/html/index.html'
            }
        }
    }
}

