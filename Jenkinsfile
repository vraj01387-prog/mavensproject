pipeline {
    agent any
 
    stages {
 
       
 
        stage('Build') {
            steps {
                echo "Building the application..."
            }
        }
 
        stage('Test') {
            steps {
                echo "Running tests..."
            }
        }
 
        stage('Deploy') {
            steps {
                echo "Deploying application..."
            }
        }
    }
 
    post {
        success {
            echo "Pipeline completed successfully."
        }
 
        failure {
            echo "Pipeline failed."
        }
 
        always {
            echo "Pipeline execution finished."
        }
    }
}

    
