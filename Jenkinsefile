pipeline {
    agent any
    stages {
        stage('Build') {
          steps {
            echo "Building the project"
            }   
        }
        post {
          success {
            emailext body: 'email sent from jenkins', subject: 'my subject', to: 'raghupattar2504@gmail.com'
            }
          }
    } 
}  
