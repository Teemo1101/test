pipeline {
    agent {
        docker {
            image 'maven:3.9.9-eslipse-temurin-21-alpine'
        }
    }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}