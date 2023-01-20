pipeline {
    agent any
    environment {
        PATH = "opt/apache-maven-3.8.7/bin:$PATH"
        }
    stages{
      stage("clone code")  {
            steps {
                script {
                    git 'https://github.com/alimelus/sample-project-maven';
            }
            }
            }
        stage("mvn build") {
            steps {
                    sh 'mvn clean package'
         
                }
                }
            }
            }
