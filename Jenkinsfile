pipeline {
    agent any
    stages {
        stage('Build') {

        }
        stage('test') {

        }
        stage('deploy') {

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