pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
               sh 'mvn -B compile'
            }
        }
        stage('Test') {
            steps {
               sh 'mvn -B test'
            }
        }
        stage('Deploy') {
            steps {
               sh 'mvn -B deploy'
            }
        }
    }
}
