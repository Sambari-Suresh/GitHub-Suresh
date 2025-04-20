pipeline {
    agent any
    stages {
        stage ('build') {
            steps {
                script {
                    echo "hello world"
                }
            }
        }
        stage ('production') {
            steps {
                script {
                    echo "hello big world"
                }
            }
        }
        stage ('test') {
            steps {
                script {
                    echo "test hello world"
                }
            }
        }
    }
}