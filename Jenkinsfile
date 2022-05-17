pipeline {
    agent any
    stages {
        stage('Hello') {
            steps {
               echo 'Hello World'
               sleep 5
            }
       }
                
         stage('Build') {
            steps {
               echo 'Build step'
               sleep 5
              
            }
        }
          stage('Test') {
            steps {
               echo 'Test step'
               sleep 4
                
            }
        }
        
          stage('Deploy') {
            steps {
                echo 'Deploy step'
                sleep 4
                
            }
        }
    }
}
