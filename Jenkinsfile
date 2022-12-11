pipeline {
    agent any

    stages {
        stage('Git Clone') {
            steps {
                echo 'Git Clone'
            }
        }
        stage('Build & Test') {
            parallel {
                stage('Build') {
                    steps {
                        echo 'Build'
                    }
                }
                stage('Test') {
                    steps {
                        echo 'Test'
                    }
                }
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy'
            }
        }
        stage('Last Step') {
            steps {
                echo 'Last Step'
            }
        }
    }
}
