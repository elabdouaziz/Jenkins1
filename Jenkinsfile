/*Jenkinsfile (Declarative Pipeline)*/
/* Requires the Docker Pipeline plugin */
pipeline {
    agent any { docker { image 'maven:3.9.9-eclipse-temurin-21-alpine' } }
    stages {
        stage('build') {
            steps {
                echo 'test'
                sh 'mvn --version'
            }
        }
    }
}
