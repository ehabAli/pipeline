pipeline {
    agent any

    stages {
        stage('Hello DEV') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hello Test') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Hello DevOps') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
