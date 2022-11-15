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
        stage('maven version') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
