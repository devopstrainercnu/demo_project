pipeline {
    agent any
    stages {
        stage('Compile') {
            steps { 
                sh 'mvn clean package'
            }
        }
        stage('test') {
            steps { 
                sh 'mvn test'
            }
        }
        stage('package') {
            steps { 
                sh 'mvn package'
            }
        }
    }
}
