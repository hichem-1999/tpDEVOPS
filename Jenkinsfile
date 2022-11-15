pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
         stage('bye') {
            steps {
                echo 'bye World'
            }
        }
         stage('java') {
            steps {
                bat 'java --version'
            }
        }
        stage('maven version') {
            steps {
                bat 'mvn --version'
            }
        }
    }
}
