def gv

pipeline {
    agent any
    stages {
        
         stage("build app ") {
            steps {
                script {
                    sh 'npm install'
                   
                }
            }
        }
       
        
        stage("build image") {
            steps {
                script {
                    sh 'docker-compose build '
                    sh 'docker-compose up -d '
                   
                }
            }
        }
        stage("deploy") {
            steps {
                script {
                    echo "deploying"
                  
                }
            }
        }
    }   
}
