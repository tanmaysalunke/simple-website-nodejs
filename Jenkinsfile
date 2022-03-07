pipeline {
    agent any
    tools { nodejs "node" }
    stages {
        stage('Hello World Take 3') {
            steps {
                sh "npm install"
            }
        }
        stage('Deploy') {
            steps {
                sh "npm start"
            }
        }
    }
}
