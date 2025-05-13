pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/your-username/your-repo.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Build step...'
                // sh './build.sh' (uncomment if needed)
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // sh './test.sh' (uncomment if needed)
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // Placeholder for deploy logic
            }
        }
    }
}


