pipeline {
    agent any 
    stages {
        stage('Build') {
            steps {
                echo 'Build!' 
            }
        }
        stage('Test') {
            steps {
                echo 'Tested!' 
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployed!' 
            }
        }
	}
        post{
           always{
               echo 'Success or Failure'
           } 
           success{
               echo 'Success'
           } 
           failure{
               echo 'Failure'
           } 
        }
   
}
