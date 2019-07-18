pipeline {
    agent any
    stages {
        stage('---clean---') {
            steps {
                sh "mvn build"
            }
        }
        stage('--test--') {
            steps {
                sh "mvn test"
            }
        }
        stage('--package--') {
            steps {
                sh "mvn package"
            }
        }
    }
}
