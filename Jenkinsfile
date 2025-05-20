pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script{
                    sh """
                        echo "Hello, This is build"
                    """
                }
            }
        }
        stage('Test') {
            steps {
                script{
                    sh """
                        echo "Hello, This is Test"
                    """
                }
            }
        }
        stage('Deploy') {
            steps {
                script{
                    sh """
                        echo "Hello, This is Deploy"
                    """
                }
            }
        }
    }
}