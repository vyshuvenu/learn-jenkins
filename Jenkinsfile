pipeline {
    agent any

    stages {
         stage('compile') {
            steps {
                echo 'compile'
            }
        }
         stage('test') {
            steps {
                echo 'test'
            }
        }
         stage('code-q') {
            steps {
                echo 'code quality'
            }
         }
          stage('code-s') {
            steps {
                echo 'code seccurity'
            }
        } 
        stage('deploy') {
            steps {
                echo 'deploy'
            }
         }  
    }
}