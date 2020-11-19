pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                sh 'echo "Build - Hello World"'
                sh 'echo ${BRANCH_NAME}'
            }
        }
        stage('Test') { 
            steps {
                sh 'echo "Test - Hello World"'
            }
        }
        stage('Deploy') { 
            steps {
                sh 'echo "Deploy - Hello World"'
            }
        }       
    }
}
