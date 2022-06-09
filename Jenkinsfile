pipeline {

   agent any
    
    tools {maven 'maven'}
    
    stages {
        stage('Compile') {
            steps {
                script {
                    sh "mvn clean compile"
                }
            }
        }
        stage('Unit Test') {
            steps {
                script {
                    sh "mvn test"
                }
            }
        }
        stage('package') {
            steps {
                script {
                    sh "mvn package"
                }
            }
        }
            }
        }
    }
}
