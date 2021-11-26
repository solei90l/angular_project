def gv

pipeline {
    agent any
    stages {
       
        stage("TESTING  ") {
          when {
            expression{
              BRANCH_NAME=='dev'
            }
          }
            steps {
                script {
                    echo "TESTING IN $BRANCH_NAME "
                 
                }
            }
        }
        stage("build image") {
            steps {
                script {
                    echo "building image"
                   
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
