pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo "Building the application..."
            }

        }
        stage('test') {
            steps {
                echo "testing the application..."
            }

        }
        stage('deploy') {
            steps {
                echo "deploying the application..."
            }

        }
    }
    post {
        always {
            echo "this section always runs" // echo command here is groovy , not shell scripting 
        }
        success {
            echo " this section runs only when pipeline is success"
        }
        failure {
            echo "this section runs only when pipeline is failure"
        }

    }
    
}