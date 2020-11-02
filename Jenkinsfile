pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
               sh 'mvn -B package -DskipTests=true'
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
