pipeline{
    agent any
    
     stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
    
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}
}
