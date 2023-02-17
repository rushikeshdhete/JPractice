pipeline {
    agent any 
    stages {
         stage('Run') { 
             steps {
                 bat "node practice.js"
             }
         }
        stage('message') { 
            steps {
                // 
                bat "echo succeffull"
            }
        }
    }
}